---
layout: relation
title: 'det'
shortdef: 'determiner'
udver: '2'
---

The relation determiner (`det`) holds between a nominal head and its [determiner](DET). In Classical Armenian, only one subtype of words with UPOS DET, the articles, can take the relation `det`. By contrast, pronominal adjectives and quantifiers, which can have adpositions and articles as their own dependencies, are attached to their head with the [amod](xcl-dep/amod) relation.

~~~ sdparse
Եւ փրկեցաւ կին ն ի ժամէ ն յ այնմանէ : \n And the woman was made whole from that [from] hour .
amod(ժամէ, այնմանէ)
det(ժամէ, ն)
case(ժամէ, ի)
case(այնոսիկ, յ)
~~~

In a relative clause, the enclitic definite article is commonly attached to the word occupying the second position in the clause, even when it is a personal verb form. In such cases, it is conventionally linked to the relative pronoun at the beginning of the cause:

~~~ sdparse
որ էջ ն յ երկնից \n he that came down from heaven 
nsubj(էջ, որ)
det(որ, ն)
~~~

### References

Jensen, Hans. 1959. _Altarmenische Grammatik._ Heidelberg: Winter.

Klein, Jared. 2017. The syntax of Armenian. In: J. Klein et al. (eds.), _Handbook of comparative and historical Indo-European linguistics_. Berlin, Boston: Walter de Gruyter: 1097‒1115.

de Lamberterie, Charles. 1997. L’article dans la relative en arménien classique. In: E. Crespo, J. L. García Ramón (eds.), _Berthold Delbrück y la sintaxis indoeuropea hoy. Actas del Coloquio de la Indogermanische Gesellschaft Madrid, 21−24 de septiembre de 1994_. Wiesbaden: Reichert: 311−326.