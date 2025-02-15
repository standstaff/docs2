---
layout: relation
title: 'cc'
shortdef: 'coordinating conjunction'
udver: '2'
---


[cc]() is the dependency relation between  a coordinating conjunction  like _και_ or _αλλά_ and the predicate it introduces.

<!--
TODO
a [coordinating conjunction](../pos/CCONJ)
-->

~~~ sdparse
Ο οδηγός ενοχλήθηκε και άρχισε να κορνάρει .
cc(άρχισε, και)
~~~

~~~ sdparse
Είπε μα δεν τόλμησε
cc(τόλμησε, μα)
~~~

*"μα" is tagged as cc only in the case that is used as the "αλλά". 

A coordinating conjunction may be used to introduce a main sentence. Again, the [cc]() dependency is used.  

<!--
and it depends on the root predicate of the sentence.
(In fact there is a coordination that spans multiple sentences.
We cannot attach a word to the first conjunct because it is in another sentence.
Thus we attach it to the first conjunct available in the current sentence: its main predicate.)
-->
~~~ sdparse
Το σύστημα , όμως , δεν εφαρμόστηκε .
cc(εφαρμόστηκε, όμως)
~~~

~~~ sdparse
Όμως πέρασε ένας χρόνος και το σύστημα δεν εφαρμόστηκε
cc(πέρασε, όμως)
cc(εφαρμόστηκε, και)
~~~

For more on coordination, see the [conj]() relation.
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:32 CET -->
