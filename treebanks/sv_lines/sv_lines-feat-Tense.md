---
layout: base
title:  'Statistics of Tense in UD_Swedish-LinES'
udver: '2'
---

## Treebank Statistics: UD_Swedish-LinES: Features: `Tense`

This feature is universal.
It occurs with 2 different values: `Past`, `Pres`.

10954 tokens (12%) have a non-empty value of `Tense`.
2076 types (15%) occur at least once with a non-empty value of `Tense`.
1515 lemmas (15%) occur at least once with a non-empty value of `Tense`.
The feature is used with 3 part-of-speech tags: <tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> (6780; 7% instances), <tt><a href="sv_lines-pos-AUX.html">AUX</a></tt> (3541; 4% instances), <tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt> (633; 1% instances).

### `VERB`

6780 <tt><a href="sv_lines-pos-VERB.html">VERB</a></tt> tokens (60% of all `VERB` tokens) have a non-empty value of `Tense`.

The most frequent other feature values with which `VERB` and `Tense` co-occurred: <tt><a href="sv_lines-feat-Mood.html">Mood</a></tt><tt>=Ind</tt> (6770; 100%), <tt><a href="sv_lines-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (6729; 99%), <tt><a href="sv_lines-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (6099; 90%).

`VERB` tokens may have the following values of `Tense`:

* `Past` (4531; 67% of non-empty `Tense`): <em>sa, var, hade, gick, kom, såg, sade, tog, fanns, fick</em>
* `Pres` (2249; 33% of non-empty `Tense`): <em>har, är, finns, vet, kommer, säger, gör, ser, tror, visas</em>
* `EMPTY` (4575): <em>ta, göra, se, gå, komma, använda, bli, få, ha, ge</em>

<table>
  <tr><th>Paradigm <i>säga</i></th><th><tt>Pres</tt></th><th><tt>Past</tt></th></tr>
  <tr><td><tt><tt><a href="sv_lines-feat-Voice.html">Voice</a></tt><tt>=Act</tt></tt></td><td><em>säger</em></td><td><em>sa, sade</em></td></tr>
  <tr><td><tt><tt><a href="sv_lines-feat-Voice.html">Voice</a></tt><tt>=Pass</tt></tt></td><td><em>sägs</em></td><td></td></tr>
</table>

### `AUX`

3541 <tt><a href="sv_lines-pos-AUX.html">AUX</a></tt> tokens (89% of all `AUX` tokens) have a non-empty value of `Tense`.

The most frequent other feature values with which `AUX` and `Tense` co-occurred: <tt><a href="sv_lines-feat-VerbForm.html">VerbForm</a></tt><tt>=Fin</tt> (3541; 100%), <tt><a href="sv_lines-feat-Voice.html">Voice</a></tt><tt>=Act</tt> (3541; 100%), <tt><a href="sv_lines-feat-Mood.html">Mood</a></tt><tt>=Ind</tt> (3521; 99%).

`AUX` tokens may have the following values of `Tense`:

* `Past` (1790; 51% of non-empty `Tense`): <em>var, hade, skulle, kunde, ville, borde, fick, vore, blev, kom</em>
* `Pres` (1751; 49% of non-empty `Tense`): <em>är, kan, har, måste, vill, kommer, ska, skall, får, bör</em>
* `EMPTY` (441): <em>vara, ha, varit, kunna, få, kunnat, vilja, bli, blivit, fått</em>

<table>
  <tr><th>Paradigm <i>vara</i></th><th><tt>Pres</tt></th><th><tt>Past</tt></th></tr>
  <tr><td><tt><tt><a href="sv_lines-feat-Mood.html">Mood</a></tt><tt>=Ind</tt></tt></td><td><em>är</em></td><td><em>var</em></td></tr>
  <tr><td><tt><tt><a href="sv_lines-feat-Mood.html">Mood</a></tt><tt>=Sub</tt></tt></td><td><em>vore</em></td><td><em>vore</em></td></tr>
</table>

### `ADJ`

633 <tt><a href="sv_lines-pos-ADJ.html">ADJ</a></tt> tokens (10% of all `ADJ` tokens) have a non-empty value of `Tense`.

The most frequent other feature values with which `ADJ` and `Tense` co-occurred: <tt><a href="sv_lines-feat-VerbForm.html">VerbForm</a></tt><tt>=Part</tt> (633; 100%), <tt><a href="sv_lines-feat-Case.html">Case</a></tt><tt>=Nom</tt> (629; 99%), <tt><a href="sv_lines-feat-Degree.html">Degree</a></tt><tt>=Pos</tt> (627; 99%), <tt><a href="sv_lines-feat-Gender.html">Gender</a></tt><tt>=EMPTY</tt> (476; 75%), <tt><a href="sv_lines-feat-Number.html">Number</a></tt><tt>=EMPTY</tt> (375; 59%).

`ADJ` tokens may have the following values of `Tense`:

* `Past` (342; 54% of non-empty `Tense`): <em>taget, flyttade, dolda, beredd, grupperade, intresserad, komplicerat, anpassad, civiliserade, rostade</em>
* `Pres` (291; 46% of non-empty `Tense`): <em>följande, motsvarande, strålande, beroende, grundläggande, levande, lysande, bländande, flygande, glänsande</em>
* `EMPTY` (5672): <em>andra, själv, hela, samma, första, annat, flera, många, stor, enda</em>

`Tense` seems to be **lexical feature** of `ADJ`. 100% lemmas (433) occur only with one value of `Tense`.

## Relations with Agreement in `Tense`

The 10 most frequent relations where parent and child node agree in `Tense`:
<tt>VERB --[<tt><a href="sv_lines-dep-conj.html">conj</a></tt>]--> VERB</tt> (1109; 82%),
<tt>VERB --[<tt><a href="sv_lines-dep-appos.html">appos</a></tt>]--> VERB</tt> (10; 56%),
<tt>VERB --[<tt><a href="sv_lines-dep-ccomp.html">ccomp</a></tt>]--> AUX</tt> (8; 57%),
<tt>VERB --[<tt><a href="sv_lines-dep-acl-cleft.html">acl:cleft</a></tt>]--> VERB</tt> (5; 56%),
<tt>AUX --[<tt><a href="sv_lines-dep-conj.html">conj</a></tt>]--> VERB</tt> (4; 80%),
<tt>VERB --[<tt><a href="sv_lines-dep-dislocated.html">dislocated</a></tt>]--> VERB</tt> (4; 57%),
<tt>AUX --[<tt><a href="sv_lines-dep-advcl.html">advcl</a></tt>]--> VERB</tt> (2; 67%),
<tt>ADJ --[<tt><a href="sv_lines-dep-appos.html">appos</a></tt>]--> ADJ</tt> (1; 100%),
<tt>AUX --[<tt><a href="sv_lines-dep-nsubj.html">nsubj</a></tt>]--> ADJ</tt> (1; 100%),
<tt>VERB --[<tt><a href="sv_lines-dep-appos.html">appos</a></tt>]--> AUX</tt> (1; 100%).

