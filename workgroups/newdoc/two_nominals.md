---
layout: base
title:  'Two Nominals'
udver: '2'
---

# Two Nominals

A nominal is a subtree headed by a common noun ([NOUN]()), proper noun ([PROPN]()) or pronoun ([PRON]()). Some nominals may be headed by a symbol ([SYM]()) if it represents a noun. Other words such as adjectives, numerals or determiners can be promoted to the head position if the main noun is elided. And words of most categories can act as nominals if they are mentioned rather than used. Note that the term ‘subtree’ is meant here to include selected but not necessarily all descendants of the head. A nominal may act as a predicate of a clause and then some of its dependents will attach at the clausal level and will not be considered part of the nominal.

There is a number of options how to connect two nominals with a relation. The first question to answer is whether one of the nominals is a clear head and the other clearly modifies it. In the typical case, the modifier nominal can be removed without rendering the sentence ungrammatical, and it refines the meaning of the head nominal. For example, English _border patrol_ denotes a special type of _patrol_, and _the man with the yellow hat_ is a special type of _man_. On the other hand, semantic compositionality is not a necessary condition and head-dependent relations are extended to similarly connected nominals where the meaning is noncompositional: for instance, a _prairie dog_ is not a _dog_ (neither a _prairie_).

## If there is a clear head

The default relation between the head and the modifier nominal is [nmod](). Some languages may have language-specific criteria that allow to separate noun-noun compounds from other noun-noun modifications; then the [compound]() relation is used. (Note that this relation can be also used for compounds where the parts are not nominals.) In other languages, such as German or Swedish, noun-noun compounds are written as one word and the `compound` relation is not needed. In yet other languages, the traditional grammar may define compounds on semantic grounds but their morphosyntactic behavior does not differ from ordinary head-modifier structures, so there is no reason not to use the `nmod` relation. For example, French _chemin de fer_ (lit. _path of iron_) “railroad” follows the same syntactic pattern as other, more compositional noun-noun modifications.

English is an example of a language where it makes sense to use the `compound` relation to connect two nominals. In noun-noun compounds, the dependent nominal precedes the head nominal, and there are restrictions on how the dependent nominal itself can be further modified. A determiner can precede the whole compound _(the prairie dog)_ but it cannot be inserted between the modifier and the head _(*the prairie the dog)_; the determiner before the compound modifies directly the head of the compound, not its first part. The head can be pluralized but the modifier cannot. On the other hand, in the ordinary `nmod` relation the modifier usually has some sort of case marking, either the possessive suffix _(the dog's tail)_ or a preposition _(the tail of the dog)_. In both cases the modifier can be pluralized and can have its own determiner (in the case of a prepositional modifier, both the head and the modifier can have a determiner). Remember that these rules are specific to English; other languages may have different rules or may not be able to separate `compound` from `nmod` at all.

## If there is no clear head

Several relations are available and they are always directed from the first nominal to the second nominal (in the order of utterance, i.e., they go left-to-right if the language uses a left-to-right writing system).

If the two nominals denote two different entities that together have the same grammatical function in the sentence, they are connected with the [conj]() relation and we have coordination of nominals. Coordination is typically recognizable by a coordinating conjunction ([CCONJ]()) but it is not a requirement. There are examples of asyndetic coordination where the conjuncts are delimited by a comma or pause, as in English _Sunlight lit up the fine <b>hairs</b> on her arm, the embroidered <b>flowers</b> on the collar of her white shirt._

If the two nominals participate in denoting one entity, the default relation to connect them is [flat]() (which may also be used to connect other nodes that are not nominals). Typical examples are personal names: we can say that _John Smith_ is a special type of _John_ as well as a special type of _Smith_, but none of the names governs the other and either of them can be omitted. In many languages this analysis extends to titles and occupations, as in English _president Barack Obama_.

Some languages may have language-specific criteria that allow to separate apposition from simple flat sequences of nouns; then the [appos]() relation is used. For example in English, the criterion is that the second (i.e., technically dependent) nominal in apposition has its own determiner and possibly other modifiers; the two nominals are typically separated by a comma in writing: in _Robert Mugabe, the former president of Zimbabwe_, there is a `flat` relation from _Robert_ to _Mugabe_, an `appos` relation from _Robert_ to _president_, and an `nmod` relation from _president_ to _Zimbabwe_. Furthermore, in appositions the two nominals can typically be reordered: _the former president of Zimbabwe, Robert Mugabe._ Note that non-UD grammars and theories may use a broader notion of apposition, which covers constructions that will not lead to the `appos` relation in UD. Also remember that the rules in this example are specific for English. Other languages may have different rules or may not be able to separate `appos` from `flat` at all.