---
layout: relation
title: 'amod'
shortdef: 'adjectival modifier'
udver: '2'
---

An adjectival modifier of a noun (or pronoun) is any adjectival phrase that serves to modify the noun (or pronoun).

~~~ sdparse
կերակուր նորա էր մարախ եւ մեղր վայրենի \n his meat was locusts and wild honey
amod(մեղր, վայրենի)
amod(honey, wild)
~~~

In UD_Classical_Armenian-CAVaL, `amod` is also applied to pronominal adjectives amd qualifiers. Although these word classes belong to [determiners](xcl-pos/DET), they can have adpositions and articles as their own dependencies, which disallows to assign them the [det](xcl-dep/det) relation.

~~~ sdparse
ի քարանցս յ այսցանէ \n from these stones
amod(քարանցս, այսցանէ)
case(քարանցս, ի)
case(այսցանէ, յ)
~~~