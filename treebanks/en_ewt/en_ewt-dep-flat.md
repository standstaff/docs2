---
layout: base
title:  'Statistics of flat in UD_English-EWT'
udver: '2'
---

## Treebank Statistics: UD_English-EWT: Relations: `flat`

This relation is universal.

2386 nodes (1%) are attached to their parents as `flat`.

2386 instances of `flat` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.46898575020956.

The following 10 pairs of parts of speech are connected with `flat`: <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt> (2098; 88% instances), <tt><a href="en_ewt-pos-X.html">X</a></tt>-<tt><a href="en_ewt-pos-X.html">X</a></tt> (201; 8% instances), <tt><a href="en_ewt-pos-NUM.html">NUM</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (69; 3% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (6; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-X.html">X</a></tt> (5; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt>-<tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt> (2; 0% instances), <tt><a href="en_ewt-pos-INTJ.html">INTJ</a></tt>-<tt><a href="en_ewt-pos-INTJ.html">INTJ</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-PROPN.html">PROPN</a></tt>-<tt><a href="en_ewt-pos-NOUN.html">NOUN</a></tt> (1; 0% instances), <tt><a href="en_ewt-pos-SYM.html">SYM</a></tt>-<tt><a href="en_ewt-pos-NUM.html">NUM</a></tt> (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 flat	color:blue
1	Ben	Ben	PROPN	NNP	Number=Sing	6	nsubj	6:nsubj	_
2	Goodger	Goodger	PROPN	NNP	Number=Sing	1	flat	1:flat	_
3	is	be	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	6	cop	6:cop	_
4	the	the	DET	DT	Definite=Def|PronType=Art	6	det	6:det	_
5	lead	lead	ADJ	JJ	Degree=Pos	6	amod	6:amod	_
6	engineer	engineer	NOUN	NN	Number=Sing	0	root	0:root	_
7	for	for	ADP	IN	_	9	case	9:case	_
8	Mozilla	Mozilla	PROPN	NNP	Number=Sing	9	compound	9:compound	_
9	Firefox	Firefox	PROPN	NNP	Number=Sing	6	nmod	6:nmod:for	SpaceAfter=No
10	.	.	PUNCT	.	_	6	punct	6:punct	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 flat	color:blue
1	A	a	X	FW	Foreign=Yes	0	root	0:root	_
2	la	la	X	FW	Foreign=Yes	1	flat	1:flat	_
3	guerre	guerre	X	FW	Foreign=Yes	1	flat	1:flat	_
4	c'est	c'est	X	FW	Foreign=Yes	1	flat	1:flat	_
5	comme	comme	X	FW	Foreign=Yes	1	flat	1:flat	_
6	a	a	X	FW	Foreign=Yes	1	flat	1:flat	_
7	la	la	X	FW	Foreign=Yes	1	flat	1:flat	_
8	guerre	guerre	X	FW	Foreign=Yes	1	flat	1:flat	SpaceAfter=No
9	!	!	PUNCT	.	_	1	punct	1:punct	_

~~~


~~~ conllu
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 14 flat	color:blue
1	HAS	have	AUX	VBZ	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	2	aux	2:aux	_
2	MOVED	move	VERB	VBN	Tense=Past|VerbForm=Part	0	root	0:root	_
3	TO	to	ADP	IN	_	6	case	6:case	_
4	4783	4783	NUM	CD	NumForm=Digit|NumType=Card	6	nummod	6:nummod	_
5	Bay	Bay	PROPN	NNP	Number=Sing	6	compound	6:compound	_
6	Rd	Rd	PROPN	NNP	Number=Sing	2	obl	2:obl:to	_
7	Saginaw	Saginaw	PROPN	NNP	Number=Sing	6	appos	6:appos	SpaceAfter=No
8	,	,	PUNCT	,	_	9	punct	9:punct	_
9	Michigan	Michigan	PROPN	NNP	Number=Sing	7	appos	7:appos	_
10	48604	48604	NUM	CD	NumForm=Digit|NumType=Card	6	appos	6:appos	_
11	(	(	PUNCT	-LRB-	_	12	punct	12:punct	SpaceAfter=No
12	989	989	NUM	CD	NumForm=Digit|NumType=Card	6	list	6:list	ExtPos=PROPN|FlatType=Phone|SpaceAfter=No
13	)	)	PUNCT	-RRB-	_	12	punct	12:punct	SpaceAfter=No
14	755-1109	755-1109	NUM	CD	NumForm=Digit|NumType=Card	12	flat	12:flat	_

~~~


