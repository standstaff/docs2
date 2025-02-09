---
layout: base
title:  'Statistics of acl:relcl in UD_Portuguese-Porttinari'
udver: '2'
---

## Treebank Statistics: UD_Portuguese-Porttinari: Relations: `acl:relcl`

This relation is a language-specific subtype of <tt><a href="pt_porttinari-dep-acl.html">acl</a></tt>.

1913 nodes (1%) are attached to their parents as `acl:relcl`.

1912 instances of `acl:relcl` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.11657083115525.

The following 23 pairs of parts of speech are connected with `acl:relcl`: <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (1240; 65% instances), <tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (349; 18% instances), <tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (139; 7% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt> (50; 3% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-ADJ.html">ADJ</a></tt> (35; 2% instances), <tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_porttinari-pos-ADJ.html">ADJ</a></tt> (16; 1% instances), <tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt> (14; 1% instances), <tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt> (13; 1% instances), <tt><a href="pt_porttinari-pos-NUM.html">NUM</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (11; 1% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt> (10; 1% instances), <tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt> (7; 0% instances), <tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_porttinari-pos-ADJ.html">ADJ</a></tt> (6; 0% instances), <tt><a href="pt_porttinari-pos-X.html">X</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (5; 0% instances), <tt><a href="pt_porttinari-pos-ADV.html">ADV</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (3; 0% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-ADV.html">ADV</a></tt> (3; 0% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-NUM.html">NUM</a></tt> (2; 0% instances), <tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt>-<tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_porttinari-pos-ADV.html">ADV</a></tt> (2; 0% instances), <tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt>-<tt><a href="pt_porttinari-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="pt_porttinari-pos-ADJ.html">ADJ</a></tt>-<tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt> (1; 0% instances), <tt><a href="pt_porttinari-pos-PRON.html">PRON</a></tt>-<tt><a href="pt_porttinari-pos-AUX.html">AUX</a></tt> (1; 0% instances), <tt><a href="pt_porttinari-pos-SYM.html">SYM</a></tt>-<tt><a href="pt_porttinari-pos-VERB.html">VERB</a></tt> (1; 0% instances), <tt><a href="pt_porttinari-pos-X.html">X</a></tt>-<tt><a href="pt_porttinari-pos-NOUN.html">NOUN</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 acl:relcl	color:blue
1	Em	em	ADP	_	_	3	case	3:case	_
2	a	o	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	3	det	3:det	_
3	semana	semana	NOUN	_	Gender=Fem|Number=Sing	7	obl	5:nsubj|7:obl:em	_
4	que	que	PRON	_	PronType=Rel	5	nsubj	3:ref	_
5	vem	vir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	3	acl:relcl	3:acl:relcl	SpaceAfter=No
6	,	,	PUNCT	_	_	3	punct	3:punct	_
7	vence	vencer	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	_
8	a	o	DET	_	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	9	det	9:det	_
9	folha	folha	NOUN	_	Gender=Fem|Number=Sing	7	nsubj	7:nsubj	_
10	de	de	ADP	_	_	11	case	11:case	_
11	setembro	setembro	NOUN	_	Gender=Masc|Number=Sing	9	nmod	9:nmod:de	SpaceAfter=No
12	.	.	PUNCT	_	_	7	punct	7:punct	SpaceAfter=No

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 acl:relcl	color:blue
1	Quem	quem	PRON	_	PronType=Ind	5	nsubj	5:nsubj	_
2	investe	investir	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	1	acl:relcl	1:acl:relcl	_
3	em	em	ADP	_	_	4	case	4:case	_
4	fundos	fundo	NOUN	_	Gender=Masc|Number=Plur	2	obl	2:obl:em	_
5	conhece	conhecer	VERB	_	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	0:root	_
6	muito	muito	ADV	_	_	7	advmod	7:advmod	_
7	bem	bem	ADV	_	_	5	advmod	5:advmod	_
8	o	o	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	9	det	9:det	_
9	come-cotas	come-cotas	NOUN	_	Number=Plur	5	obj	5:obj	SpaceAfter=No
10	.	.	PUNCT	_	_	5	punct	5:punct	SpaceAfter=No

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 acl:relcl	color:blue
1	Outro	outro	DET	_	Gender=Masc|Number=Sing|PronType=Ind	2	det	2:det	_
2	tucano	tucano	NOUN	_	Gender=Masc|Number=Sing	0	root	0:root	SpaceAfter=No
3	,	,	PUNCT	_	_	4	punct	4:punct	_
4	José	José	PROPN	_	_	2	parataxis	2:parataxis|8:nsubj	_
5	Serra	Serra	PROPN	_	_	4	flat:name	4:flat:name	_
6	que	que	PRON	_	PronType=Rel	8	nsubj	4:ref	_
7	o	o	PRON	_	Case=Acc|Gender=Masc|Number=Sing|Person=3|PronType=Prs	8	obj	8:obj	_
8	diga	dizer	VERB	_	Mood=Sub|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	acl:relcl	4:acl:relcl	SpaceAfter=No
9	.	.	PUNCT	_	_	2	punct	2:punct	SpaceAfter=No

~~~


