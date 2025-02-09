---
layout: base
title:  'Statistics of Gender in UD_Coptic-Scriptorium'
udver: '2'
---

## Treebank Statistics: UD_Coptic-Scriptorium: Features: `Gender`

This feature is universal.
It occurs with 2 different values: `Fem`, `Masc`.

This is a <a href="../../u/overview/feat-layers.html">layered feature</a> with the following layers: <tt><a href="cop_scriptorium-feat-Gender.html">Gender</a></tt>, <tt><a href="cop_scriptorium-feat-Gender-psor.html">Gender[psor]</a></tt>.

9846 tokens (17%) have a non-empty value of `Gender`.
72 types (3%) occur at least once with a non-empty value of `Gender`.
42 lemmas (2%) occur at least once with a non-empty value of `Gender`.
The feature is used with 2 part-of-speech tags: <tt><a href="cop_scriptorium-pos-PRON.html">PRON</a></tt> (4992; 9% instances), <tt><a href="cop_scriptorium-pos-DET.html">DET</a></tt> (4854; 9% instances).

### `PRON`

4992 <tt><a href="cop_scriptorium-pos-PRON.html">PRON</a></tt> tokens (53% of all `PRON` tokens) have a non-empty value of `Gender`.

The most frequent other feature values with which `PRON` and `Gender` co-occurred: <tt><a href="cop_scriptorium-feat-Number.html">Number</a></tt><tt>=Sing</tt> (4992; 100%), <tt><a href="cop_scriptorium-feat-Definite.html">Definite</a></tt><tt>=Def</tt> (4563; 91%), <tt><a href="cop_scriptorium-feat-PronType.html">PronType</a></tt><tt>=Prs</tt> (4563; 91%), <tt><a href="cop_scriptorium-feat-Person.html">Person</a></tt><tt>=3</tt> (3739; 75%).

`PRON` tokens may have the following values of `Gender`:

* `Fem` (1071; 21% of non-empty `Gender`): ⲥ, ⲧⲉ, ⲉ, ⲛⲧⲟⲥ, ⲉⲣⲟ, ⲁ, ⲛⲧⲟ, ⲙⲙⲟ, ⲣ, ⲁⲣ
* `Masc` (3921; 79% of non-empty `Gender`): ϥ, ⲕ, ⲡⲉ, ⲅ, ⲛⲧⲟϥ, ⲡ, ⲛⲧⲟⲕ, ⲉⲕϣⲁⲛ, ⲉϥϣⲁⲛ, ⲉϥⲉ
* `EMPTY` (4362): ⲩ, ⲟⲩ, ⲓ, ⲛ, ⲧⲛ, ⲧⲉⲧⲛ, ⲛⲓⲙ, ⲥⲉ, ϯ, ϥ

<table>
  <tr><th>Paradigm <i>ⲡⲉ</i></th><th><tt>Masc</tt></th><th><tt>Fem</tt></th></tr>
  <tr><td><tt></tt></td><td>ⲡⲉ, ⲡ</td><td>ⲧⲉ, ⲧ</td></tr>
</table>

`Gender` seems to be **lexical feature** of `PRON`. 96% lemmas (24) occur only with one value of `Gender`.

### `DET`

4854 <tt><a href="cop_scriptorium-pos-DET.html">DET</a></tt> tokens (66% of all `DET` tokens) have a non-empty value of `Gender`.

The most frequent other feature values with which `DET` and `Gender` co-occurred: <tt><a href="cop_scriptorium-feat-Definite.html">Definite</a></tt><tt>=Def</tt> (4854; 100%), <tt><a href="cop_scriptorium-feat-Number.html">Number</a></tt><tt>=Sing</tt> (4854; 100%), <tt><a href="cop_scriptorium-feat-Number-psor.html">Number[psor]</a></tt><tt>=EMPTY</tt> (3901; 80%), <tt><a href="cop_scriptorium-feat-Person.html">Person</a></tt><tt>=EMPTY</tt> (3901; 80%), <tt><a href="cop_scriptorium-feat-Poss.html">Poss</a></tt><tt>=EMPTY</tt> (3871; 80%), <tt><a href="cop_scriptorium-feat-PronType.html">PronType</a></tt><tt>=Art</tt> (3461; 71%).

`DET` tokens may have the following values of `Gender`:

* `Fem` (1311; 27% of non-empty `Gender`): ⲧ, ⲧⲉ, ⲧⲉϥ, ⲧⲉⲓ, ⲧⲁ, ⲧⲉⲕ, ⲧⲁⲓ, ⲧⲉⲩ, ⲧⲉⲥ, ⲧⲟⲩ
* `Masc` (3543; 73% of non-empty `Gender`): ⲡ, ⲡⲉ, ⲡⲁ, ⲡⲉϥ, ⲡⲁⲓ, ⲡⲉⲓ, ⲡⲉⲕ, ⲡⲉⲛ, ⲡⲉⲥ, ⲡⲉⲩ
* `EMPTY` (2522): ⲛ, ⲟⲩ, ϩⲉⲛ, ⲛⲉ, ⲛⲉϥ, ⲛⲁⲓ, ⲕⲉ, ⲩ, ⲛⲁ, ⲙ

<table>
  <tr><th>Paradigm <i>ⲡ</i></th><th><tt>Masc</tt></th><th><tt>Fem</tt></th></tr>
  <tr><td><tt></tt></td><td>ⲡ, ⲡⲉ</td><td>ⲧ, ⲧⲉ, ⲑ</td></tr>
</table>

## Relations with Agreement in `Gender`

The 10 most frequent relations where parent and child node agree in `Gender`:
<tt>DET --[<tt><a href="cop_scriptorium-dep-cop.html">cop</a></tt>]--> PRON</tt> (71; 100%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-conj.html">conj</a></tt>]--> DET</tt> (7; 88%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-acl-relcl.html">acl:relcl</a></tt>]--> DET</tt> (5; 71%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-appos.html">appos</a></tt>]--> DET</tt> (4; 80%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-parataxis.html">parataxis</a></tt>]--> DET</tt> (4; 80%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-nmod.html">nmod</a></tt>]--> DET</tt> (3; 100%),
<tt>PRON --[<tt><a href="cop_scriptorium-dep-dislocated.html">dislocated</a></tt>]--> DET</tt> (3; 60%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-nsubj.html">nsubj</a></tt>]--> DET</tt> (2; 100%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-obl-unmarked.html">obl:unmarked</a></tt>]--> PRON</tt> (2; 100%),
<tt>DET --[<tt><a href="cop_scriptorium-dep-dislocated.html">dislocated</a></tt>]--> DET</tt> (1; 100%).

