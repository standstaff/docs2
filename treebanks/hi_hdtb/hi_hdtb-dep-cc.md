---
layout: base
title:  'Statistics of cc in UD_Hindi-HDTB'
udver: '2'
---

## Treebank Statistics: UD_Hindi-HDTB: Relations: `cc`

This relation is universal.

6428 nodes (2%) are attached to their parents as `cc`.

6419 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.96095208462974.

The following 12 pairs of parts of speech are connected with `cc`: <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (2314; 36% instances), <tt><a href="hi_hdtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (2244; 35% instances), <tt><a href="hi_hdtb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (1471; 23% instances), <tt><a href="hi_hdtb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (321; 5% instances), <tt><a href="hi_hdtb-pos-PRON.html">PRON</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (28; 0% instances), <tt><a href="hi_hdtb-pos-NUM.html">NUM</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (22; 0% instances), <tt><a href="hi_hdtb-pos-ADV.html">ADV</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (13; 0% instances), <tt><a href="hi_hdtb-pos-DET.html">DET</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (11; 0% instances), <tt><a href="hi_hdtb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="hi_hdtb-pos-SCONJ.html">SCONJ</a></tt> (1; 0% instances), <tt><a href="hi_hdtb-pos-AUX.html">AUX</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="hi_hdtb-pos-PART.html">PART</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances), <tt><a href="hi_hdtb-pos-X.html">X</a></tt>-<tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 14 11 cc	color:blue
1	अर्धा	अर्धा	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	9	nsubj	_	ChunkId=NP|ChunkType=head|LTranslit=ardhā|SpaceAfter=No|Tam=0|Translit=ardhā|Vib=0
2	,	,	PUNCT	SYM	_	1	punct	_	ChunkId=NP|ChunkType=child|LTranslit=,|Translit=,
3	जो	जो	PRON	PRP	Case=Nom|Number=Sing|Person=3|PronType=Prs	4	nsubj	_	ChunkId=NP2|ChunkType=head|LTranslit=jo|Tam=0|Translit=jo|Vib=0
4	चौकोर	चौकोर	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	1	acl:relcl	_	ChunkId=NP3|ChunkType=head|CxnElt=5:Existential-CopPred.Pivot|LTranslit=caukora|Tam=0|Translit=caukora|Vib=0
5	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	ChunkId=VGF|ChunkType=head|Cxn=Existential-CopPred|LTranslit=hai|SpaceAfter=No|Stype=declarative|Tam=hE|Translit=hai|Vib=है
6	,	,	PUNCT	SYM	_	1	punct	_	ChunkId=VGF|ChunkType=child|LTranslit=,|Translit=,
7	अंदर	अंदर	ADV	NST	AdpType=Post|Case=Acc|Gender=Masc|Number=Sing|Person=3	9	advmod	_	AltTag=ADV-NOUN|ChunkId=NP4|ChunkType=head|LTranslit=aṁdara|Translit=aṁdara|Vib=0_से
8	से	से	ADP	PSP	AdpType=Post	7	case	_	ChunkId=NP4|ChunkType=child|LTranslit=se|Translit=se
9	पोली	पोला	ADJ	JJ	Gender=Fem|Number=Sing	0	root	_	ChunkId=JJP|ChunkType=head|LTranslit=polā|Translit=polī
10	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	9	cop	_	ChunkId=VGF2|ChunkType=head|LTranslit=hai|Stype=declarative|Tam=hE|Translit=hai|Vib=है
11	और	और	CCONJ	CC	_	14	cc	_	ChunkId=CCP|ChunkType=head|LTranslit=aura|Translit=aura
12	अपेक्षाकृत	अपेक्षाकृत	ADV	RB	_	13	advmod	_	ChunkId=RBP|ChunkType=head|LTranslit=apekṣākr̥ta|Translit=apekṣākr̥ta
13	नवीन	नवीन	ADJ	JJ	_	14	xcomp	_	ChunkId=JJP2|ChunkType=head|LTranslit=navīna|Translit=navīna
14	बनी	बनना	VERB	VM	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|VerbForm=Part|Voice=Act	9	conj	_	ChunkId=VGF3|ChunkType=head|LTranslit=bananā|Stype=declarative|Tam=yA|Translit=banī|Vib=या_है
15	है	है	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	14	aux	_	ChunkId=VGF3|ChunkType=child|LTranslit=hai|Tam=hE|Translit=hai|Vib=है
16	।	।	PUNCT	SYM	_	9	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 cc	color:blue
1	इन	यह	DET	DEM	Case=Acc|Number=Plur|Person=3|PronType=Dem	3	det	_	ChunkId=NP|ChunkType=child|LTranslit=yaha|Translit=ina
2	सभी	सभी	DET	QF	PronType=Ind	3	det	_	ChunkId=NP|ChunkType=child|LTranslit=sabhī|Translit=sabhī
3	स्‍थानों	स्थान	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	12	obl	_	ChunkId=NP|ChunkType=head|LTranslit=sthāna|Tam=0|Translit=sthānoṁ|Vib=0_पर
4	पर	पर	ADP	PSP	AdpType=Post	3	case	_	ChunkId=NP|ChunkType=child|LTranslit=para|Translit=para
5	इन	यह	DET	DEM	Case=Acc|Number=Plur|Person=3|PronType=Dem	6	det	_	ChunkId=NP2|ChunkType=child|LTranslit=yaha|Translit=ina
6	भस्‍मों	भस्म	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	12	obl	_	ChunkId=NP2|ChunkType=head|LTranslit=bhasma|Tam=0|Translit=bhasmoṁ|Vib=0
7	और	और	CCONJ	CC	_	8	cc	_	ChunkId=CCP|ChunkType=head|LTranslit=aura|Translit=aura
8	अस्‍थियों	अस्थि	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	6	conj	_	ChunkId=NP3|ChunkType=head|LTranslit=asthi|Tam=0|Translit=asthiyoṁ|Vib=0_के_ऊपर
9	के	के	ADP	PSP	AdpType=Post	8	case	_	ChunkId=NP3|ChunkType=child|LTranslit=ke|Translit=ke
10	ऊपर	ऊपर	ADP	NST	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing|Person=3	8	case	_	AltTag=ADP-NOUN|ChunkId=NP3|ChunkType=child|LTranslit=ūpara|Translit=ūpara
11	स्‍तूप	स्‍तूप	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	12	obj	_	ChunkId=NP4|ChunkType=head|LTranslit=stūpa|Tam=0|Translit=stūpa|Vib=0
12	बनाए	बनाना	VERB	VM	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part|Voice=Pass	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=banānā|Stype=declarative|Tam=yA|Translit=banāe|Vib=या_जा+या1
13	गए	जाना	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part	12	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=jānā|Tam=yA1|Translit=gae|Vib=या1
14	।	।	PUNCT	SYM	_	12	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 cc	color:blue
1	लेकिन	लेकिन	CCONJ	CC	_	11	cc	_	ChunkId=CCP|ChunkType=head|LTranslit=lekina|SpaceAfter=No|Translit=lekina
2	,	,	PUNCT	SYM	_	11	punct	_	ChunkId=CCP|ChunkType=child|LTranslit=,|Translit=,
3	इस	यह	DET	DEM	Case=Acc|Number=Sing|Person=3|PronType=Dem	4	det	_	ChunkId=NP|ChunkType=child|LTranslit=yaha|Translit=isa
4	समझौते	समझौता	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	11	obl	_	ChunkId=NP|ChunkType=head|LTranslit=samajhautā|Tam=0|Translit=samajhaute|Vib=0_से
5	से	से	ADP	PSP	AdpType=Post	4	case	_	ChunkId=NP|ChunkType=child|LTranslit=se|Translit=se
6	राजद	राजद	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	10	nmod	_	ChunkId=NP2|ChunkType=head|LTranslit=rājada|Tam=0|Translit=rājada|Vib=0
7	और	और	CCONJ	CC	_	8	cc	_	ChunkId=CCP2|ChunkType=head|LTranslit=aura|Translit=aura
8	माकपा	माकपा	PROPN	NNP	Case=Acc|Gender=Fem|Number=Sing|Person=3	6	conj	_	ChunkId=NP3|ChunkType=head|LTranslit=mākapā|Tam=0|Translit=mākapā|Vib=0_का
9	की	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Fem|Number=Plur	8	case	_	ChunkId=NP3|ChunkType=child|LTranslit=kā|Translit=kī
10	भवें	भौं	NOUN	NN	Case=Nom|Gender=Fem|Number=Plur|Person=3	11	nsubj	_	ChunkId=NP4|ChunkType=head|LTranslit=bhauṁ|Tam=0|Translit=bhaveṁ|Vib=0
11	तन	तनना	VERB	VM	Gender=Fem|Number=Plur|Person=3|Voice=Act	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=tananā|Stype=declarative|Tam=0|Translit=tana|Vib=0_जा+या१_है
12	गई	जाना	AUX	VAUX	Aspect=Perf|Gender=Fem|Number=Plur|VerbForm=Part	11	aux	_	ChunkId=VGF|ChunkType=child|LTranslit=jānā|Tam=yA1|Translit=gaī|Vib=या१
13	हैं	है	AUX	VAUX	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	11	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=hai|Tam=hE|Translit=haiṁ|Vib=है
14	।	।	PUNCT	SYM	_	11	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


