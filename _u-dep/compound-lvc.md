---
layout: relation
title: 'compound:lvc'
shortdef: 'light verb construction'
udver: '2'
---

This subtype of [compound]() covers light verbs.
In a  light-verb construction the verb does not have much semantic content.
The semantics of the construction are determined by the non-head word,
often a noun or adjective.

~~~ sdparse
Onlar treni tercih ediyor . \n They prefer the train .
compound:lvc(ediyor, tercih)
obj(ediyor, treni)
subj(ediyor, Onlar)
~~~

Most common verbs that act like as a light verb is _et-_.
However, many other are possible.

~~~ sdparse
Yıllarca çile çektiler . \n They suffered for years .
compound:lvc(çektiler, çile)
~~~

Although the semantically loaded component of a light-verb construction is
generally an adjective or a noun,
it is common to observe verbs in this position particularly in code-switching settings.

~~~ sdparse
Partiyi  cancel ettik . \n We canceled the party
compound:lvc(ettik, cancel)
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:38 CET -->
