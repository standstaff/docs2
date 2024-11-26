---
layout: relation
title: 'nmod:unmarked'
shortdef : 'unmarked nominal modifier'
udver: '2'
---

This relation is a subtype of the [nmod]() relation that applies
when a non-possessive modifier within a nominal takes the form of a 
nominal lacking a preposition (a.k.a. a noun phrase). It is 
"unmarked" in that, unlike most `nmod`s, it has no adposition or
genitive marking.

`nmod:unmarked` merges two older subtypes, `nmod:npmod` and `nmod:tmod`.
It has a clause-level countepart: [obl:unmarked]().

Examples include:

(i) temporal modifiers

~~~ sdparse
Are you free for lunch some day this week ?
nmod:unmarked(lunch, day)
det(day, some)
nmod:unmarked(day, week)
det(week, this)
~~~

(ii) rate expressions with meaning equivalent to "per"

~~~ sdparse
IBM earned $ 5 a share
nmod:unmarked($, share)
~~~

(iii) elementary properties

~~~ sdparse
I want that color kitten
nmod:unmarked(kitten, color)
~~~

~~~ sdparse
a pizza the size of the sun
nmod:unmarked(pizza, size)
~~~

(iv) emphatic reflexive pronouns

~~~ sdparse
Einstein himself was in attendance .
nmod:unmarked(Einstein, himself)
~~~

(v) "a couple" as pre-head quantifier

~~~ sdparse
You can have a couple/NOUN cookies .
det(couple, a)
nmod:unmarked(cookies, couple)
~~~

## In names and dates

** DRAFT - NOT YET IMPLEMENTED **

For naming patterns that incorporate a locational relation
without a preposition (often punctuated with a comma or dash),
we treat the locational element as `nmod:unmarked`.
Multiple such elements may nest (but note that [flat]() connects composite
type+number names).
This includes:

(i) a location-elaboration in an address (such as the state or country given after a city,
or a numbered unit in relation to a building or street):

~~~ sdparse
110/NUM Sproul/PROPN Hall/PROPN , Berkeley/PROPN , California/PROPN , USA/PROPN
nmod:unmarked(110, Hall)
compound(Hall, Sproul)
nmod:unmarked(Hall, Berkeley)
nmod:unmarked(Berkeley, California)
nmod:unmarked(California, USA)
~~~

~~~ sdparse
221B/PROPN Baker/PROPN St./PROPN , Apt./PROPN E/PROPN
nmod:unmarked(221B, St.)
compound(St., Baker)
flat(Apt., E)
nmod:unmarked(221B, Apt.)
~~~

Note that the apartment is technically located within the building identified by a house number,
but the apartment is presented as a refinement of the location (possibly separated by a comma),
so it is considered the modifier.

(ii) an institutional branch or campus

~~~ sdparse
University/PROPN of/ADP Wisconsin/PROPN – Madison/PROPN
nmod(University, Wisconsin)
nmod:unmarked(University, Madison)
~~~

(iii) larger units within a juxtaposition-based temporal expression
(regardless of word order and cardinal vs. ordinal date)

~~~ sdparse
8/NUM[NumType=Card] October/PROPN 1963/NUM[NumType=Card]
nmod:unmarked(8, October)
nmod:unmarked(October, 1963)
~~~

~~~ sdparse
October/PROPN 8/NUM[NumType=Card] , 1963/NUM[NumType=Card]
nmod:unmarked(8, October)
nmod:unmarked(October, 1963)
~~~

~~~ sdparse
October/PROPN 8th/NUM[NumType=Ord] , 1963/NUM[NumType=Card]
nmod:unmarked(8th, October)
nmod:unmarked(October, 1963)
~~~

** TODO: postal codes, am/pm, time zones (maybe [list]()?) **

**History:** Prior to release 2.15, case (i) (temporal modifiers)
had a separate subtype called [nmod:tmod](), and [nmod:npmod]()
was used for the non-temporal ones.
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:06 CET -->
