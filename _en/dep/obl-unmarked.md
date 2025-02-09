---
layout: relation
title: 'obl:unmarked'
shortdef : 'adpositionless oblique'
udver: '2'
---

This relation is a subtype of the [obl]() relation that applies
when an oblique takes the form of a nominal lacking a preposition
(a.k.a. a noun phrase). It is "unmarked" in that, unlike most obliques,
it has no adposition.

`obl:unmarked` merges two older subtypes, `obl:npmod` and `obl:tmod`. It has a nominal-level counterpart: [nmod:unmarked]().

Examples include:

(i) a time, manner, or extent adverbial in a clause

~~~ sdparse
Last night , I swam in the pool
obl:unmarked(swam, night)
~~~

~~~ sdparse
Let's do things my way .
obl:unmarked(do, way)
~~~

(ii) a measure phrase, which is the relation between the head of an
adjectival/adverbial or prepositional phrase and the head of a measure
phrase modifying it:

~~~ sdparse
The director is 65 years old
obl:unmarked(old, years)
~~~

~~~ sdparse
6 feet long
obl:unmarked(long, feet)
~~~


(iii) noun phrases giving an extent to a verb, which are not objects:

~~~ sdparse
Shares eased a fraction
obl:unmarked(eased, fraction)
~~~


(iv) floating reflexives

~~~ sdparse
The silence is itself significant
obl:unmarked(significant, itself)
~~~


and (v) certain other absolutive nominal constructions.

**History:** Prior to release 2.15, temporal adverbials (see (i)) had a separate subtype called [obl:tmod](), and [obl:npmod]() was used for the non-temporal ones.
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:22 CET -->
