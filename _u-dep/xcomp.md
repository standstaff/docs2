---
layout: relation
title: 'xcomp'
shortdef: 'open clausal complement'
udver: '2'
---

An open clausal complement (`xcomp`) of a verb or an adjective is (i) a core argument of the verb, (ii) which is without its own subject and (iii) for which the 
reference of the subject is necessarily determined by an argument
external to the `xcomp`. The third requirement is often referred to as *obligatory control*.
An `xcomp` can also be described as a predicative complement. The subject of the `xcomp` is normally, but not always, controlled by the object of the next higher
clause, if there is one, or else by the subject of the next higher
clause.
These clauses tend to be non-finite in many languages,
but they can be finite as well. The name `xcomp` is
borrowed from Lexical-Functional Grammar (see Joan Bresnan, 2001, _Lexical-Functional Syntax_, chapter on “Predication Relations”).

~~~ sdparse
We expect them to change their minds
xcomp(expect, change)
obj(expect, them)
~~~

~~~ sdparse
Sue asked George to respond to her offer
xcomp(asked, respond)
iobj(asked, George)
~~~

~~~ sdparse
I started to work there yesterday
xcomp(started, work)
~~~

~~~ sdparse
You look great
xcomp(look, great)
~~~

~~~ sdparse
I consider him a fool
obj(consider, him)
xcomp(consider, fool)
~~~

~~~ sdparse
Louise struck me as a fool
obj(struck, me)
case(fool, as)
xcomp(struck, fool)
~~~

~~~ sdparse
I consider her honest
obj(consider, her)
xcomp(consider, honest)
~~~

~~~ sdparse
I regard her as honest
obj(regard, her)
mark(honest, as)
xcomp(regard, honest)
~~~

~~~ sdparse
We got COVID-19 under control
obj(got, COVID-19)
case(control, under)
xcomp(got, control)
~~~

~~~ sdparse
Susan is liable to be arrested
cop(liable, is)
xcomp(liable, arrested)
~~~

The predicative complement can be headed by various parts of speech, including a VERB, ADJ, or NOUN. A nominal predicative complement can be marked by a preposition (in English, often but not always by _as_). The `xcomp`-taking predicate of the higher clause can be a VERB or ADJ.

Contrast `xcomp` with other complement clauses where there is an overt subject or no obligatory control, which use [ccomp]():

~~~ sdparse
He says that you like to swim
ccomp(says, like)
~~~

~~~ sdparse
I suggest eating now before the food gets cold
ccomp(suggest, eating)
~~~

### The Inherited Subject Criterion

In examples like “I consider her honest”, the UD analysis corresponds to traditional grammar and what was termed "raising to object" in early generative grammar: the nominal "her" in these constructions is treated as the object of the higher clause (as its accusative morphology and ability to passivize suggests).

Note that the above condition “without its own subject” does not mean that a
clause is an `xcomp` just because its subject is not _overt._ The subject must be necessarily inherited from a fixed position in the higher clause. That is, there should be no available interpretation where the subject of the lower clause may be distinct
from the specified role of the upper clause. In cases where the missing subject may or must be distinct from a fixed role in the higher clause, `ccomp` should be used instead, as below.  This includes cases of arbitrary subjects and anaphoric control. In the following example, the subject of _start_ or _starting_ does not have to be the boss, it is any contextually relevant person or group of people. In addition, in these cases, the complement clause can often be replaced by a pronoun like _it_ or _that_ and it can sometimes be passivized (_Starting the project was recommended by the boss_).

~~~ sdparse
The boss said to start the project
ccomp(said, start)
~~~

~~~ sdparse
The boss recommended starting the project
ccomp(recommended, starting)
~~~



Pro-drop languages have clauses where the subject is not present as a separate word,
yet it is inherently present (and often deducible from the form of the verb).
The relation between clauses with pro-drop may or may not be `xcomp`.
The implicit subjects of a subordinate clause and a higher clause may be coincidentally coreferent, warranting [ccomp]() or [advcl]():

~~~ sdparse
Píšu , protože jsem to slíbil . \n I-write , because I-have it promised .
advcl(Píšu, slíbil)
advcl(I-write, promised)
aux(slíbil, jsem)
aux(promised, I-have)
obj(slíbil, to)
obj(promised, it)
mark(slíbil, protože)
mark(promised, because)
~~~

~~~ sdparse
Slíbil jsem , že budu psát . \n Promised I-have , that I-will write .
ccomp(Slíbil, psát)
ccomp(Promised, write)
aux(Slíbil, jsem)
aux(Promised, I-have)
aux(psát, budu)
aux(write, I-will)
mark(psát, že)
mark(write, that)
~~~

It is only `xcomp` if the implicit subject depends on an argument from a higher clause (one cannot be varied without the other):

~~~ sdparse
Slíbil jsem psát . \n Promised I-have to-write .
xcomp(Slíbil, psát)
xcomp(Promised, to-write)
aux(Slíbil, jsem)
aux(Promised, I-have)
~~~

### Secondary Predicates

*The following is excerpted from [a more detailed discussion of secondary predicates](../overview/complex-syntax.html#secondary-predicates).*

The `xcomp` relation is also used in constructions that are known as _secondary predicates_ or _predicatives_.
Examples:

* _She declared the cake beautiful._
* _She declared the cake a success._

We could paraphrase the sentence using a subordinate clause: _She declared that the cake was beautiful._
There are two predicates mixed in one clause: 1. she declared something, and 2. the cake was beautiful (according to her opinion).
The secondary predicate will be attached to the main predicate as an `xcomp`:

~~~ sdparse
She declared the cake beautiful .
nsubj(declared, She)
obj(declared, cake)
xcomp(declared, beautiful)
~~~

The subject of "declared" is again obligatorily controlled by a role in the higher clause. In the enhanced representation, there is an additional subject link showing the secondary predication:

~~~ sdparse
She declared the cake beautiful .
nsubj(declared, She)
obj(declared, cake)
xcomp(declared, beautiful)
nsubj(beautiful, cake)
~~~

A Czech example:

~~~ sdparse
jmenovat někoho generálem \n to-appoint someone as-a-general
obj(jmenovat, někoho)
xcomp(jmenovat, generálem)
~~~

Remember that `xcomp` is used for core arguments of predicates
so it will not be used for non-core instances of secondary predication.
For instance, in _She entered the room sad_ we also have a double predication
(she entered the room; she was sad).
But _sad_ is not a core argument of _enter:_ leaving it out will neither affect grammaticality
nor significantly alter the meaning of the verb.
On the other hand, leaving out _beautiful_ in _she declared the cake beautiful_
will either render the sentence ungrammatical or lead to a different interpretation of _declared._

The result is that in _She entered the room sad_, _sad_ is considered a modifier (not complement) of the verb,
with the relation [advcl]() instead of `xcomp`.
(This was [changed](/changes.html#optional-depictives) from the previous approach which analyzed the secondary predication directly with [acl](),
because the nominal predicand is not always overt, and even when it is, the adjective does not really belong to the same nominal phrase.)

~~~ sdparse
She entered the room sad .
nsubj(entered, She)
det(room, the)
obj(entered, room)
advcl(entered, sad)
punct(entered, .)
~~~

~~~ sdparse
Entering the room sad is not recommended .
csubj(recommended, Entering)
det(room, the)
obj(Entering, room)
advcl(Entering, sad)
cop(recommended, is)
advmod(recommended, not)
punct(recommended, .)
~~~

Notice that *while* can be inserted before *sad*, clearly marking it as a clause.

A Czech example:

~~~ sdparse
Vstoupila do místnosti smutná . \n She-entered to room sad .
advcl(Vstoupila, smutná)
advcl(She-entered, sad)
~~~

There is no need to decide whether an example like the following is a depictive or a manner adverbial:

~~~ sdparse
Linda found the money walking our dog .
nsubj(found, Linda)
det(money, the)
obj(found, money)
advcl(found, walking)
det(dog, our)
obj(walking, dog)
punct(found, .)
~~~

The optional secondary predication or controlled adjunct subject relation can be represented with an enhanced dependency edge
in addition to the [advcl]() relation.

Some other cases that _could_ be regarded as secondary predicates are just treated as obliques. In particular, locative arguments of verbs are always treated as obliques:

~~~ sdparse
She put a book on the table .
nsubj(put, She)
det(book, a)
obj(put, book)
case(table, on)
det(table, the)
obl(put, table)
punct(put, .)
~~~


<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:30 CET -->
