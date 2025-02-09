---
layout: relation
title: 'obl:npmod'
shortdef : 'noun phrase as adverbial modifier'
udver: '2'
---

**⚠️ DEPRECATED: Beginning with the version 2.15 release,
most English corpora will use the new [obl:unmarked]() relation instead. ⚠️**

This relation is a subtype of the [obl]() relation, which captures
the following cases where something syntactically a noun phrase is
used as an adverbial modifier in a sentence:


(i) a measure phrase, which is the relation between the head of an
adjectival/adverbial or prepositional phrase and the head of a measure
phrase modifying it:

~~~ sdparse
The director is 65 years old
obl:npmod(old, years)
~~~

~~~ sdparse
6 feet long
obl:npmod(long, feet)
~~~


(ii) noun phrases giving an extent to a verb, which are not objects:

~~~ sdparse
Shares eased a fraction
obl:npmod(eased, fraction)
~~~


(iv) floating reflexives

~~~ sdparse
The silence is itself significant
obl:npmod(significant, itself)
~~~


and (v) certain other absolutive nominal constructions.

A temporal modifier [obl:tmod]() is a subclass of [obl]() which is
distinguished as a separate relation.

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:20 CET -->
