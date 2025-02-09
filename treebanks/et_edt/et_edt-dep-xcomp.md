---
layout: base
title:  'Statistics of xcomp in UD_Estonian-EDT'
udver: '2'
---

## Treebank Statistics: UD_Estonian-EDT: Relations: `xcomp`

This relation is universal.

5805 nodes (1%) are attached to their parents as `xcomp`.

4767 instances of `xcomp` (82%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.66356589147287.

The following 24 pairs of parts of speech are connected with `xcomp`: <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-VERB.html">VERB</a></tt> (3580; 62% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (928; 16% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt> (910; 16% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-VERB.html">VERB</a></tt> (126; 2% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt> (70; 1% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (59; 1% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-PRON.html">PRON</a></tt> (53; 1% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt> (24; 0% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-ADV.html">ADV</a></tt> (8; 0% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-VERB.html">VERB</a></tt> (7; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt> (7; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-VERB.html">VERB</a></tt> (7; 0% instances), <tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (6; 0% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-PRON.html">PRON</a></tt> (4; 0% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (4; 0% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-NUM.html">NUM</a></tt> (3; 0% instances), <tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt>-<tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-ADV.html">ADV</a></tt>-<tt><a href="et_edt-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-AUX.html">AUX</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-PRON.html">PRON</a></tt>-<tt><a href="et_edt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="et_edt-pos-ADJ.html">ADJ</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="et_edt-pos-VERB.html">VERB</a></tt>-<tt><a href="et_edt-pos-SYM.html">SYM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 xcomp	color:blue
1	Ma	mina	PRON	P	Case=Nom|Number=Sing|Person=1|PronType=Prs	2	nsubj	2:nsubj|3:nsubj	Arg=kalduma_Arg_0
2	kaldun	kalduma	VERB	V	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	0:root	Verb=kalduma
3	arvama	arvama	VERB	V	Case=Ill|VerbForm=Sup|Voice=Act	2	xcomp	2:xcomp	SpaceAfter=No|Verb=arvama
4	,	,	PUNCT	Z	_	9	punct	9:punct	_
5	et	et	SCONJ	J	_	9	mark	9:mark	_
6	Vermeeri	Vermeer	PROPN	S	Case=Gen|Number=Sing	7	nmod	7:nmod	NE=B-Per
7	saatus	saatus	NOUN	S	Case=Nom|Number=Sing	9	nsubj:cop	9:nsubj	_
8	oli	olema	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	9	cop	9:cop	_
9	teistsugune	teist_sugune	PRON	P	Case=Nom|Number=Sing|PronType=Dem	3	ccomp	3:ccomp	Arg=arvama_Arg_1|SpaceAfter=No
10	.	.	PUNCT	Z	_	2	punct	2:punct	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 6 xcomp	color:blue
1	Teises	teine	ADJ	N	Case=Ine|Number=Sing|NumForm=Word|NumType=Ord	2	amod	2:amod	_
2	sõidus	sõit	NOUN	S	Case=Ine|Number=Sing	3	obl	3:obl	_
3	jäi	jääma	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	0:root	Verb=jääma_4
4	Kuismanen	Kuismanen	PROPN	S	Case=Nom|Number=Sing	3	nsubj	3:nsubj|6:nsubj	Arg=jääma_Arg_1|NE=B-Per
5	Behrensile	Behrens	PROPN	S	Case=All|Number=Sing	6	obl	6:obl	NE=B-Per
6	püüdmatuks	püüdmatu	ADJ	A	Case=Tra|Degree=Pos|Number=Sing	3	xcomp	3:xcomp	Arg=jääma_Arg_5|SpaceAfter=No
7	.	.	PUNCT	Z	_	3	punct	3:punct	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 xcomp	color:blue
1	Ja	ja	CCONJ	J	_	3	cc	3:cc	_
2	siis	siis	ADV	D	_	3	advmod	3:advmod	_
3	läks	minema	VERB	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	0:root	Verb=minema_2
4	tööks	töö	NOUN	S	Case=Tra|Number=Sing	3	xcomp	3:xcomp	Arg=minema_Arg_5
5	...	...	PUNCT	Z	_	3	punct	3:punct	_

~~~


