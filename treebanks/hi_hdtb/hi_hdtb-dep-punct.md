---
layout: base
title:  'Statistics of punct in UD_Hindi-HDTB'
udver: '2'
---

## Treebank Statistics: UD_Hindi-HDTB: Relations: `punct`

This relation is universal.

23455 nodes (7%) are attached to their parents as `punct`.

19014 instances of `punct` (81%) are left-to-right (parent precedes child).
Average distance between parent and child is 6.7861010445534.

The following 15 pairs of parts of speech are connected with `punct`: <tt><a href="hi_hdtb-pos-VERB.html">VERB</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (15739; 67% instances), <tt><a href="hi_hdtb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (3218; 14% instances), <tt><a href="hi_hdtb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (2951; 13% instances), <tt><a href="hi_hdtb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (1007; 4% instances), <tt><a href="hi_hdtb-pos-PRON.html">PRON</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (199; 1% instances), <tt><a href="hi_hdtb-pos-NUM.html">NUM</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (155; 1% instances), <tt><a href="hi_hdtb-pos-ADV.html">ADV</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (124; 1% instances), <tt><a href="hi_hdtb-pos-DET.html">DET</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (38; 0% instances), <tt><a href="hi_hdtb-pos-PART.html">PART</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (10; 0% instances), <tt><a href="hi_hdtb-pos-ADP.html">ADP</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="hi_hdtb-pos-CCONJ.html">CCONJ</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (4; 0% instances), <tt><a href="hi_hdtb-pos-AUX.html">AUX</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="hi_hdtb-pos-INTJ.html">INTJ</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (2; 0% instances), <tt><a href="hi_hdtb-pos-SCONJ.html">SCONJ</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances), <tt><a href="hi_hdtb-pos-X.html">X</a></tt>-<tt><a href="hi_hdtb-pos-PUNCT.html">PUNCT</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 punct	color:blue
1	आइए	आना	VERB	VM	Mood=Sub|Number=Sing|Person=2|Polite=Form|VerbForm=Fin|Voice=Act	2	vocative	_	ChunkId=VGF|ChunkType=head|LTranslit=ānā|Stype=imperative|Tam=eM|Translit=āie|Vib=एं
2	करें	करना	VERB	VM	Mood=Sub|Number=Plur|Person=3|VerbForm=Fin|Voice=Act	0	root	_	ChunkId=VGF2|ChunkType=head|LTranslit=karanā|Stype=declarative|Tam=eM|Translit=kareṁ|Vib=एं
3	सैर	सैर	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	2	compound	_	ChunkId=NP|ChunkType=head|LTranslit=saira|Tam=0|Translit=saira|Vib=0
4	-	-	PUNCT	SYM	_	2	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=-|Translit=-

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 8 punct	color:blue
1	कुशीनगर	कुशीनगर	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	3	nmod	_	ChunkId=NP|ChunkType=head|LTranslit=kuśīnagara|Tam=0|Translit=kuśīnagara|Vib=0_का
2	का	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	1	case	_	ChunkId=NP|ChunkType=child|LTranslit=kā|Translit=kā
3	महत्‍व	महत्व	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	nsubj	_	ChunkId=NP2|ChunkType=head|LTranslit=mahatva|Tam=0|Translit=mahatva|Vib=0
4	महापरिनिर्वाण	महापरिनिर्वाण	PROPN	NNPC	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	compound	_	ChunkId=NP3|ChunkType=child|LTranslit=mahāparinirvāṇa|Tam=0|Translit=mahāparinirvāṇa|Vib=0
5	मंदिर	मंदिर	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	0	root	_	ChunkId=NP3|ChunkType=head|CxnElt=7:Existential-CopPred.Pivot|LTranslit=maṁdira|Tam=0|Translit=maṁdira|Vib=0_से
6	से	से	ADP	PSP	AdpType=Post	5	case	_	ChunkId=NP3|ChunkType=child|LTranslit=se|Translit=se
7	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	ChunkId=VGF|ChunkType=head|Cxn=Existential-CopPred|LTranslit=hai|Stype=declarative|Tam=hE|Translit=hai|Vib=है
8	।	।	PUNCT	SYM	_	5	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 12 punct	color:blue
1	कुशीनगर	कुशीनगर	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	5	nmod	_	ChunkId=NP|ChunkType=head|LTranslit=kuśīnagara|Tam=0|Translit=kuśīnagara|Vib=0_का
2	का	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	1	case	_	ChunkId=NP|ChunkType=child|LTranslit=kā|Translit=kā
3	सबसे	सबसे	ADV	INTF	AdvType=Deg	4	advmod	_	AltTag=avy-ADV|ChunkId=NP2|ChunkType=child|LTranslit=sabase|Translit=sabase
4	ज्‍यादा	ज्यादा	DET	QF	PronType=Ind	5	det	_	ChunkId=NP2|ChunkType=child|LTranslit=jyādā|Translit=jyādā
5	महत्‍व	महत्व	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	7	nsubj	_	ChunkId=NP2|ChunkType=head|LTranslit=mahatva|Tam=0|Translit=mahatva|Vib=0
6	बौद्ध	बौद्ध	PROPN	NNP	Case=Nom|Gender=Masc|Number=Sing|Person=3	7	nmod	_	ChunkId=NP3|ChunkType=child|LTranslit=bauddha|Tam=0|Translit=bauddha|Vib=0
7	तीर्थ	तीर्थ	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	0	root	_	ChunkId=NP3|ChunkType=head|CxnElt=11:Existential-CopPred.Pivot|LTranslit=tīrtha|Tam=0|Translit=tīrtha|Vib=0_के_रूप_में
8	के	के	ADP	PSP	AdpType=Post|Case=Acc|Gender=Masc	7	case	_	ChunkId=NP3|ChunkType=child|LTranslit=ke|Translit=ke
9	रूप	रूप	ADP	PSP	Case=Acc|Gender=Masc	7	case	_	ChunkId=NP3|ChunkType=child|LTranslit=rūpa|Translit=rūpa
10	में	में	ADP	PSP	AdpType=Post	7	case	_	ChunkId=NP3|ChunkType=child|LTranslit=meṁ|Translit=meṁ
11	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	7	cop	_	ChunkId=VGF|ChunkType=head|Cxn=Existential-CopPred|LTranslit=hai|Stype=declarative|Tam=hE|Translit=hai|Vib=है
12	।	।	PUNCT	SYM	_	7	punct	_	ChunkId=BLK|ChunkType=head|LTranslit=.|Translit=.

~~~


