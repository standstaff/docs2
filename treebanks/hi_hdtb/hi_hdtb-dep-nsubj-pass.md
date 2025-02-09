---
layout: base
title:  'Statistics of nsubj:pass in UD_Hindi-HDTB'
udver: '2'
---

## Treebank Statistics: UD_Hindi-HDTB: Relations: `nsubj:pass`

This relation is a language-specific subtype of <tt><a href="hi_hdtb-dep-nsubj.html">nsubj</a></tt>.

558 nodes (0%) are attached to their parents as `nsubj:pass`.

546 instances of `nsubj:pass` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 6.28853046594982.

The following 5 pairs of parts of speech are connected with `nsubj:pass`: <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-NOUN.html">NOUN</a></tt> (320; 57% instances), <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-PROPN.html">PROPN</a></tt> (156; 28% instances), <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-PRON.html">PRON</a></tt> (68; 12% instances), <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt> (13; 2% instances), <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-ADJ.html">ADJ</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 nsubj:pass	color:blue
1	सेना	सेना	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing|Person=3	4	nmod	_	ChunkId=NP|ChunkType=head|LTranslit=senā|Tam=0|Translit=senā|Vib=0_का
2	की	का	ADP	PSP	AdpType=Post|Case=Acc|Gender=Fem|Number=Sing	1	case	_	ChunkId=NP|ChunkType=child|LTranslit=kā|Translit=kī
3	जबावी	जबावी	ADJ	JJ	Case=Acc	4	amod	_	ChunkId=NP2|ChunkType=child|LTranslit=jabāvī|Translit=jabāvī
4	कार्रवाई	कार्रवाई	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing|Person=3	8	obl	_	ChunkId=NP2|ChunkType=head|LTranslit=kārravāī|Tam=0|Translit=kārravāī|Vib=0_में
5	में	में	ADP	PSP	AdpType=Post	4	case	_	ChunkId=NP2|ChunkType=child|LTranslit=meṁ|Translit=meṁ
6	तीन	तीन	NUM	QC	NumType=Card	7	nummod	_	ChunkId=NP3|ChunkType=child|LTranslit=tīna|Translit=tīna
7	आतंकी	आतंकी	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	8	nsubj:pass	_	ChunkId=NP3|ChunkType=head|LTranslit=ātaṁkī|Tam=0|Translit=ātaṁkī|Vib=0
8	मारे	मारना	VERB	VM	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part|Voice=Pass	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=māranā|Stype=declarative|Tam=yA|Translit=māre|Vib=या_जा+या१
9	गए	जाना	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part	8	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=jānā|Tam=yA1|Translit=gae|Vib=या१
10	।	।	PUNCT	SYM	_	8	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 nsubj:pass	color:blue
1	रिजवी	रिजवी	PROPN	NNP	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	nsubj:pass	_	ChunkId=NP|ChunkType=head|LTranslit=rijavī|Tam=0|Translit=rijavī|Vib=0
2	समिति	समिति	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing|Person=3	4	nmod	_	ChunkId=NP2|ChunkType=head|LTranslit=samiti|Tam=0|Translit=samiti|Vib=0_का
3	के	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing|Person=3|Polite=Form	2	case	_	ChunkId=NP2|ChunkType=child|LTranslit=kā|Translit=ke
4	संयोजक	संयोजक	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	xcomp	_	ChunkId=NP3|ChunkType=head|LTranslit=saṁyojaka|Tam=0|Translit=saṁyojaka|Vib=0
5	बनाए	बनाना	VERB	VM	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|Polite=Form|VerbForm=Part|Voice=Pass	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=banānā|Stype=declarative|Tam=yA|Translit=banāe|Vib=या_जा+या१_है
6	गए	जाना	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|Polite=Form|VerbForm=Part	5	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=jānā|Tam=yA1|Translit=gae|Vib=या१
7	हैं	है	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Polite=Form|Tense=Pres|VerbForm=Fin	5	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=hai|Tam=hE|Translit=haiṁ|Vib=है
8	।	।	PUNCT	SYM	_	5	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 1 nsubj:pass	color:blue
1	उन्हें	वह	PRON	PRP	Case=Acc,Dat|Number=Plur|Person=3|PronType=Prs	5	nsubj:pass	_	ChunkId=NP|ChunkType=head|LTranslit=vaha|Tam=ko|Translit=unheṁ|Vib=को
2	भी	भी	PART	RP	_	1	dep	_	ChunkId=NP|ChunkType=child|LTranslit=bhī|Translit=bhī
3	वही	वह	DET	DEM	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Dem	4	det	_	ChunkId=NP2|ChunkType=child|LTranslit=vaha|Translit=vahī
4	लाभ	लाभ	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	obj	_	ChunkId=NP2|ChunkType=head|LTranslit=lābha|Tam=0|Translit=lābha|Vib=0
5	दिए	देना	VERB	VM	Aspect=Perf|Gender=Masc|VerbForm=Part|Voice=Act	0	root	_	ChunkId=VGF|ChunkType=head|LTranslit=denā|Stype=declarative|Tam=yA|Translit=die|Vib=या_जा+ना_चाहिए
6	जाने	जाना	AUX	VAUX	Gender=Masc|Number=Plur|VerbForm=Inf	5	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=jānā|Tam=nA|Translit=jāne|Vib=ना
7	चाहिए	चाहिए	AUX	VAUX	_	5	aux:pass	_	ChunkId=VGF|ChunkType=child|LTranslit=cāhie|Tam=0|Translit=cāhie|Vib=0
8	जो	जो	PRON	PRP	Case=Nom|Number=Plur|Person=3|PronType=Prs	11	obj	_	ChunkId=NP3|ChunkType=head|LTranslit=jo|Tam=0|Translit=jo|Vib=0
9	अल्पसंख्यकों	अल्पसंख्यक	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	11	iobj	_	ChunkId=NP4|ChunkType=head|LTranslit=alpasaṁkhyaka|Tam=0|Translit=alpasaṁkhyakoṁ|Vib=0_को
10	को	को	ADP	PSP	AdpType=Post	9	case	_	ChunkId=NP4|ChunkType=child|LTranslit=ko|Translit=ko
11	दिए	देना	VERB	VM	Aspect=Perf|Gender=Masc|Number=Plur|Person=3|VerbForm=Part|Voice=Act	4	amod	_	ChunkId=VGF2|ChunkType=head|LTranslit=denā|Stype=declarative|Tam=yA|Translit=die|Vib=या_जा+ता_है
12	जाते	जाना	AUX	VAUX	Aspect=Imp|Gender=Masc|Number=Plur|VerbForm=Part	11	aux:pass	_	ChunkId=VGF2|ChunkType=child|LTranslit=jānā|Tam=wA|Translit=jāte|Vib=ता
13	हैं	है	AUX	VAUX	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	11	aux:pass	_	ChunkId=VGF2|ChunkType=child|LTranslit=hai|Tam=hE|Translit=haiṁ|Vib=है
14	।	।	PUNCT	SYM	_	5	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


