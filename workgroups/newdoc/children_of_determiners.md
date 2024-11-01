---
layout: base
title:  'Children of Determiners'
udver: '2'
---

# Can Determiners Have Children in the Tree Structure?

This page discusses nodes that are attached to their parents via the [det]() relation. When we say _determiner_ in this text, we are referring to the relation and not to the UPOS category [DET](). Of course, there is a strong correlation between the two but it is not absolute. For example, a `DET` could be promoted when its noun is elided, then its incoming relation would be something else than `det` and the rules discussed here would not apply.

Determiners are generally considered function words in UD. As such, they are typically leaf nodes, that is, they do not have children. However, this rule is not strict and the [guidelines list some exceptions](/u/overview/syntax.html#the-status-of-function-words) for various function words including determiners.

For several years, the [UD validator](/release_checklist.html#validation) did not enforce this rule for determiners while it was doing so for other function words. The test was finally [implemented in September 2024](https://github.com/UniversalDependencies/tools/commit/1e4debd) under the label `leaf-det-clf`, [later split](https://github.com/UniversalDependencies/tools/commit/c5b8cf5ecff55c27affa8ff0eac737cb799883c8) to two tests, `leaf-det` and `leaf-clf`; since this page is about determiners and not about classifiers, we are interested in `leaf-det`. Like other similar tests for function words, it allows determiners to have children if the (universal part of the) relation between the determiner and the child is in a predefined subset:

*



//
Nathan: "such" licenses an adverbial clause: "such a player that he could get away with that"
Daniel Swanson (Hebrew): demonstrative pronouns have their own determiners. (Petr had the same thing in Classical Armenian.)
