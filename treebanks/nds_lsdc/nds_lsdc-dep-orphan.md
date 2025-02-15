---
layout: base
title:  'Statistics of orphan in UD_Low_Saxon-LSDC'
udver: '2'
---

## Treebank Statistics: UD_Low_Saxon-LSDC: Relations: `orphan`

This relation is universal.

20 nodes (0%) are attached to their parents as `orphan`.

17 instances of `orphan` (85%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.3.

The following 8 pairs of parts of speech are connected with `orphan`: <tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt>-<tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt> (10; 50% instances), <tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt>-<tt><a href="nds_lsdc-pos-ADV.html">ADV</a></tt> (3; 15% instances), <tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt>-<tt><a href="nds_lsdc-pos-ADJ.html">ADJ</a></tt> (2; 10% instances), <tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt>-<tt><a href="nds_lsdc-pos-ADP.html">ADP</a></tt> (1; 5% instances), <tt><a href="nds_lsdc-pos-PRON.html">PRON</a></tt>-<tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt> (1; 5% instances), <tt><a href="nds_lsdc-pos-PROPN.html">PROPN</a></tt>-<tt><a href="nds_lsdc-pos-ADJ.html">ADJ</a></tt> (1; 5% instances), <tt><a href="nds_lsdc-pos-PROPN.html">PROPN</a></tt>-<tt><a href="nds_lsdc-pos-ADV.html">ADV</a></tt> (1; 5% instances), <tt><a href="nds_lsdc-pos-VERB.html">VERB</a></tt>-<tt><a href="nds_lsdc-pos-NOUN.html">NOUN</a></tt> (1; 5% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 4 orphan	color:blue
1	Pastor	pastor	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	0	root	_	lemma_gml=pâstôr
2	mid	mid	ADP	_	AdpType=Prep	4	case	_	lemma_gml=mit
3	en	en	DET	_	Case=Acc,Dat|Definite=Ind|Gender=Masc|Number=Sing|PronType=Art	4	det	_	lemma_gml=êin,êine,êin
4	handgebäärde	handgebäärde	NOUN	_	Case=Acc,Dat|Gender=Masc|Number=Sing	1	orphan	_	lemma_gml=hantgebêrde|SpaceAfter=No
5	,	,	PUNCT	_	_	9	punct	_	_
6	as	as	SCONJ	_	_	9	cc	_	lemma_gml=alsô
7	wul	willen	AUX	_	Mood=Ind,Sub|Number=Sing|Person=3|Tense=Past	9	aux	_	lemma_gml=willen
8	hee	hee	PRON	_	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	9	nsubj	_	lemma_gml=hê,sê,et
9	seggen	seggen	VERB	_	VerbForm=Inf	4	acl	_	lemma_gml=seggen|SpaceAfter=No
10	:	:	PUNCT	_	_	11	punct	_	_
11	Tappen	tappe	NOUN	_	Case=Acc|Gender=Masc|Number=Plur	9	ccomp	_	lemma_gml=tappe
12	af	af	ADP	_	_	11	orphan	_	lemma_gml=af|SpaceAfter=No
13	!	!	PUNCT	_	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 32	bgColor:blue
# visual-style 32	fgColor:white
# visual-style 30	bgColor:blue
# visual-style 30	fgColor:white
# visual-style 30 32 orphan	color:blue
1	Wän	wän	SCONJ	_	_	6	mark	_	_
2	de	de	DET	_	Case=Nom|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	4	det	_	lemma_gml=dê¹
3	lutherske	luthersk	ADJ	_	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	amod	_	_
4	gelouve	gelouve	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	6	nsubj	_	_
5	en	en	DET	_	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	6	det	_	lemma_gml=êⁱn¹
6	sake	sake	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	26	advcl	_	_
7	weer	weasen	AUX	_	Mood=Sub|Number=Sing|Person=3|Tense=Past	6	cop	_	lemma_gml=wēsen²|SpaceAfter=No
8	,	,	PUNCT	_	_	12	punct	_	_
9	dee	dee	PRON	_	Case=Nom|Gender=Fem|Number=Sing|Person=3|PronType=Rel	12	nsubj	_	lemma_gml=dê¹
10	sik	sik	PRON	_	Case=Acc,Dat|Number=Sing|Person=3	12	obj	_	_
11	koupen	köypen	VERB	_	VerbForm=Inf	12	xcomp	_	_
12	leyt	låten	VERB	_	Mood=Sub|Number=Sing|Person=3	6	acl	_	SpaceAfter=No
13	,	,	PUNCT	_	_	12	punct	_	_
14	ik	ik	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	26	nsubj	_	_
15	wul	willen	AUX	_	Mood=Ind,Sub|Number=Sing|Person=1|Tense=Past	26	aux	_	_
16	ünder	under	ADP	_	AdpType=Prep	18	case	_	_
17	de	de	DET	_	Case=Acc,Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	18	det	_	lemma_gml=dê¹
18	hand	hand	NOUN	_	Case=Acc,Dat|Gender=Fem|Number=Sing	26	obl	_	_
19	vöär	vöär	ADP	_	AdpType=Prep	21	case	_	_
20	tein	tein	NUM	_	_	21	nummod	_	_
21	daler	daler	NOUN	_	Case=Acc|Gender=Masc|Number=Plur	26	obl	_	_
22	en	en	DET	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing|PronType=Art	24	det	_	lemma_gml=êⁱn¹
23	ganses	gans	ADJ	_	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing	24	amod	_	_
24	karspeal	kerspeal	NOUN	_	Case=Acc|Gender=Neut|Number=Sing	26	obj	_	_
25	leddig	leddig	ADJ	_	_	26	xcomp	_	_
26	koupen	köypen	VERB	_	VerbForm=Inf	0	root	_	SpaceAfter=No
27	;	;	PUNCT	_	_	30	punct	_	_
28	vellicht	vellicht	ADV	_	_	30	orphan	_	_
29	den	de	DET	_	Case=Acc|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	30	det	_	lemma_gml=dê¹
30	preester	preester	NOUN	_	Case=Dat|Gender=Masc|Number=Sing	26	conj	_	_
31	vyn	vyn	ADJ	_	_	30	orphan	_	_
32	mid	mid	ADV	_	_	30	orphan	_	SpaceAfter=No
33	,	,	PUNCT	_	_	30	punct	_	_
34	un	un	CCONJ	_	_	41	cc	_	lemma_gml=unde²
35	de	de	DET	_	Case=Acc|Gender=Fem|Number=Sing|PronType=Art	36	det	_	lemma_gml=dê¹
36	ware	ware	NOUN	_	Case=Acc|Gender=Fem|Number=Sing	41	obj	_	_
37	an	an	ADP	_	AdpType=Prep	40	case	_	_
38	den	de	DET	_	Case=Acc,Dat|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	40	det	_	lemma_gml=dê¹
39	lütjen	lütken	ADJ	_	Case=Acc,Dat|Degree=Pos|Gender=Masc|Number=Sing	40	amod	_	_
40	vinger	vinger	NOUN	_	Case=Acc,Dat|Gender=Masc|Number=Sing	41	obl	_	_
41	wegdrägen	wegdragen	VERB	_	VerbForm=Inf	26	conj	_	SpaceAfter=No
42	,	,	PUNCT	_	_	46	punct	_	_
43	in	in	ADP	_	AdpType=Prep	45	case	_	_
44	en	en	DET	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing|PronType=Art	45	det	_	lemma_gml=êⁱn¹
45	snuupdook	snuupdook	NOUN	_	Case=Acc|Gender=Neut|Number=Sing	46	obl	_	_
46	beknütted	beknütten	VERB	_	Aspect=Perf|VerbForm=Part	41	advcl	_	SpaceAfter=No
47	.	.	PUNCT	_	_	26	punct	_	_

~~~


~~~ conllu
# visual-style 31	bgColor:blue
# visual-style 31	fgColor:white
# visual-style 30	bgColor:blue
# visual-style 30	fgColor:white
# visual-style 30 31 orphan	color:blue
1	Wän	wän	SCONJ	_	_	6	mark	_	_
2	de	de	DET	_	Case=Nom|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	4	det	_	lemma_gml=dê¹
3	lutherske	luthersk	ADJ	_	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	4	amod	_	_
4	gelouve	gelouve	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	6	nsubj	_	_
5	en	en	DET	_	Case=Nom|Definite=Ind|Gender=Fem|Number=Sing|PronType=Art	6	det	_	lemma_gml=êⁱn¹
6	sake	sake	NOUN	_	Case=Nom|Gender=Fem|Number=Sing	26	advcl	_	_
7	weer	weasen	AUX	_	Mood=Sub|Number=Sing|Person=3|Tense=Past	6	cop	_	lemma_gml=wēsen²|SpaceAfter=No
8	,	,	PUNCT	_	_	12	punct	_	_
9	dee	dee	PRON	_	Case=Nom|Gender=Fem|Number=Sing|Person=3|PronType=Rel	12	nsubj	_	lemma_gml=dê¹
10	sik	sik	PRON	_	Case=Acc,Dat|Number=Sing|Person=3	12	obj	_	_
11	koupen	köypen	VERB	_	VerbForm=Inf	12	xcomp	_	_
12	leyt	låten	VERB	_	Mood=Sub|Number=Sing|Person=3	6	acl	_	SpaceAfter=No
13	,	,	PUNCT	_	_	12	punct	_	_
14	ik	ik	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	26	nsubj	_	_
15	wul	willen	AUX	_	Mood=Ind,Sub|Number=Sing|Person=1|Tense=Past	26	aux	_	_
16	ünder	under	ADP	_	AdpType=Prep	18	case	_	_
17	de	de	DET	_	Case=Acc,Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	18	det	_	lemma_gml=dê¹
18	hand	hand	NOUN	_	Case=Acc,Dat|Gender=Fem|Number=Sing	26	obl	_	_
19	vöär	vöär	ADP	_	AdpType=Prep	21	case	_	_
20	tein	tein	NUM	_	_	21	nummod	_	_
21	daler	daler	NOUN	_	Case=Acc|Gender=Masc|Number=Plur	26	obl	_	_
22	en	en	DET	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing|PronType=Art	24	det	_	lemma_gml=êⁱn¹
23	ganses	gans	ADJ	_	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing	24	amod	_	_
24	karspeal	kerspeal	NOUN	_	Case=Acc|Gender=Neut|Number=Sing	26	obj	_	_
25	leddig	leddig	ADJ	_	_	26	xcomp	_	_
26	koupen	köypen	VERB	_	VerbForm=Inf	0	root	_	SpaceAfter=No
27	;	;	PUNCT	_	_	30	punct	_	_
28	vellicht	vellicht	ADV	_	_	30	orphan	_	_
29	den	de	DET	_	Case=Acc|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	30	det	_	lemma_gml=dê¹
30	preester	preester	NOUN	_	Case=Dat|Gender=Masc|Number=Sing	26	conj	_	_
31	vyn	vyn	ADJ	_	_	30	orphan	_	_
32	mid	mid	ADV	_	_	30	orphan	_	SpaceAfter=No
33	,	,	PUNCT	_	_	30	punct	_	_
34	un	un	CCONJ	_	_	41	cc	_	lemma_gml=unde²
35	de	de	DET	_	Case=Acc|Gender=Fem|Number=Sing|PronType=Art	36	det	_	lemma_gml=dê¹
36	ware	ware	NOUN	_	Case=Acc|Gender=Fem|Number=Sing	41	obj	_	_
37	an	an	ADP	_	AdpType=Prep	40	case	_	_
38	den	de	DET	_	Case=Acc,Dat|Definite=Def|Gender=Masc|Number=Sing|PronType=Art	40	det	_	lemma_gml=dê¹
39	lütjen	lütken	ADJ	_	Case=Acc,Dat|Degree=Pos|Gender=Masc|Number=Sing	40	amod	_	_
40	vinger	vinger	NOUN	_	Case=Acc,Dat|Gender=Masc|Number=Sing	41	obl	_	_
41	wegdrägen	wegdragen	VERB	_	VerbForm=Inf	26	conj	_	SpaceAfter=No
42	,	,	PUNCT	_	_	46	punct	_	_
43	in	in	ADP	_	AdpType=Prep	45	case	_	_
44	en	en	DET	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing|PronType=Art	45	det	_	lemma_gml=êⁱn¹
45	snuupdook	snuupdook	NOUN	_	Case=Acc|Gender=Neut|Number=Sing	46	obl	_	_
46	beknütted	beknütten	VERB	_	Aspect=Perf|VerbForm=Part	41	advcl	_	SpaceAfter=No
47	.	.	PUNCT	_	_	26	punct	_	_

~~~


