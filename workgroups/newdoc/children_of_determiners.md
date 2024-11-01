---
layout: base
title:  'Children of Determiners'
udver: '2'
---

# Can Determiners Have Children in the Tree Structure?

This page discusses nodes that are attached to their parents via the [det]() relation. When we say _determiner_ in this text, we are referring to the relation and not to the UPOS category [DET](). Of course, there is a strong correlation between the two but it is not absolute. For example, a `DET` could be promoted when its noun is elided, then its incoming relation would be something else than `det` and the rules discussed here would not apply.

Determiners are generally considered function words in UD. As such, they are typically leaf nodes, that is, they do not have children. However, this rule is not strict and the [guidelines list some exceptions](/u/overview/syntax.html#the-status-of-function-words) for various function words including determiners.

For several years, the [UD validator](/release_checklist.html#validation) did not enforce this rule for determiners while it was doing so for other function words. The test was finally [implemented in September 2024](https://github.com/UniversalDependencies/tools/commit/1e4debd) under the label `leaf-det-clf`, [later split](https://github.com/UniversalDependencies/tools/commit/c5b8cf5ecff55c27affa8ff0eac737cb799883c8) to two tests, `leaf-det` and `leaf-clf`; since this page is about determiners and not about classifiers, we are interested in `leaf-det`. Like other similar tests for function words, it allows determiners to have children if the (universal part of the) relation between the determiner and the child is in a predefined subset:

* [goeswith]() – Like any other word, determiner may be incorrectly split to multiple tokens in writing, then the pieces must be connected via `goeswith`.
* [reparandum]() – Like any other word in spoken data, determiner may be the correct word after an incorrect fragment has been uttered, then the incorrect fragment must be attached to the determiner via `reparandum`.
* [fixed]() – This relation is used to connect tokens in fixed multiword expression that act as a function word. Multiword determiners are not common but they do occur e.g. in French _lire <b>de la</b> documentation_ “to read documentation”.
* [conj]() and [cc]() – Determiners can be coordinated (e.g. _<b>each and every</b> member_).
* [punct]() – Punctuation should normally be attached to a content word, but it must be attached to a function word if
  * the function word is the only word enclosed in paired punctuation such as brackets;
  * or if it is the only way how to avoid non-projectivity;
  * or if it separates coordinate function words.

## Light Adverbials

The [guidelines also acknowledge](/u/overview/syntax.html#function-word-modifiers) that “certain types of function words can take a restricted class of modifiers, mainly light adverbials (including negation).” They explicitly give one example that involves a determiner: _<b>not every</b> linguist_. Ideally the validator should have the list of permitted modifiers (light adverbials) for each language; as such lists are currently not available, the validator has additional deprel-level exceptions, although they potentially open the door for other adverbials that should not be allowed:

* [advmod]() – It is used to attach negative particles such as _not_ in _not every linguist_.
* [obl]() – A modifier could be semantically adverbial but syntactically expressed as a nominal rather than an adverb. In that case, it must be attached as `obl` and not as `advmod`. This exception was copied from other function words although it is unclear yet whether it is needed with determiners.

## Problematic Constructions

After the validation test was introduced, it identified problems in over 200 UD treebanks. For some of them, their maintainers suggested that the guidelines should be extended to allow additional specific constructions. The full discussion is in [Issue #1059](https://github.com/UniversalDependencies/docs/issues/1059); as it is extremely long and messy, we try to summarize the interesting points here.

### Adverbial Clauses

([Nathan Schneider](https://github.com/UniversalDependencies/docs/issues/1059#issue-2574038827))

In English, _such_ is a demonstrative determiner and it may license an [advcl](), as in [these results](https://universal.grew.fr/?custom=66f9b53a31605). The guidelines on [sufficiency and excess](/u/overview/specific-syntax.html#sufficiency-and-excess) for _so_ and similar say the `advcl` should attach to the adjective or adverb, not the noun in a case like _sufficient flour_. Then in _such a high price **that nobody could afford it**_, we may want to attach the `advcl` dependent to _such_.

Ideally, the validator should allow `advcl` specifically in English and only if the head is _such_. If there are similar constructions in other languages, they should be also registered specifically for those languages and not en bloc for the whole UD.

([Joakim Nivre](https://github.com/UniversalDependencies/docs/issues/1059#issuecomment-2452025700)) You have the choice of treating _such_ as [amod](), in which case it is unproblematic to attach an `advcl` to it. If you treat _such_ as `det`, you instead have to attach the clause to its head (that is, to the whole phrase). This is similar to how we treat some comparative constructions. (Dan Zeman) If _such_ is `amod`, then it should probably also have the [ADJ]() UPOS tag. Although it looks like the current validator will not complain if it sees a [DET]() attached as `amod` (it definitely does complain if it sees an `ADJ` attached as `det`).

### Determiners under Determiners

As the guidelines [say](/u/overview/syntax.html#the-status-of-function-words), multiple determiners are always attached directly to the head noun:

<div id="s3c" class="sd-parse">
All/DET these/DET three/NUM books/NOUN .
det(books, All)
det(books, these)
nummod(books, three)
</div>

However, some languages have constructions that look quite different from the English example above.

([Daniel Swanson](https://github.com/UniversalDependencies/docs/issues/1059#issuecomment-2400694043))

In Hebrew (both Ancient and Modern), demonstrative pronouns have their own determiners, as in “the men the these” = “these men”. It is also parallel to how adjectival modification works in Modern Hebrew. Maybe determiners under demonstratives could be allowed in some languages but not the others?

//(Petr had the same thing in Classical Armenian.)
