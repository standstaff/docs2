---
layout: base
title:  'Statistics of obj:lvc in UD_Naija-NSC'
udver: '2'
---

## Treebank Statistics: UD_Naija-NSC: Relations: `obj:lvc`

This relation is a language-specific subtype of <tt><a href="pcm_nsc-dep-obj.html">obj</a></tt>.

53 nodes (0%) are attached to their parents as `obj:lvc`.

53 instances of `obj:lvc` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.35849056603774.

The following 4 pairs of parts of speech are connected with `obj:lvc`: <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-NOUN.html">NOUN</a></tt> (45; 85% instances), <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-ADJ.html">ADJ</a></tt> (4; 8% instances), <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt> (3; 6% instances), <tt><a href="pcm_nsc-pos-VERB.html">VERB</a></tt>-<tt><a href="pcm_nsc-pos-PROPN.html">PROPN</a></tt> (1; 2% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 obj:lvc	color:blue
1	#	#	X	_	_	3	dep	_	AlignBegin=64011|AlignEnd=64514|Gloss=PUNCT
2	dey	dey	AUX	_	Aspect=Imp	3	aux	_	AlignBegin=64513|AlignEnd=64584|Gloss=IPFV
3	use	use	VERB	_	_	0	root	_	AlignBegin=64584|AlignEnd=64774|Gloss=use
4	am	am	PRON	_	Case=Acc|Number=Sing|Person=3|PronType=Prs	3	obj	_	AlignBegin=64774|AlignEnd=64974|Gloss=ACC.SG.3
5	//=	//=	X	_	_	7	dep	_	AlignBegin=64974|AlignEnd=64974|Gloss=PUNCT
6	dey	dey	AUX	_	Aspect=Imp	7	aux	_	AlignBegin=64974|AlignEnd=65063|Gloss=IPFV
7	take	take	VERB	_	_	3	parataxis:conj	_	AlignBegin=65063|AlignEnd=65263|Gloss=take
8	care	care	NOUN	_	_	7	obj:lvc	_	AlignBegin=65263|AlignEnd=65464|Gloss=care
9	of	of	ADP	_	_	10	case	_	AlignBegin=65464|AlignEnd=65644|Gloss=of
10	ourself	oursef	PRON	_	Case=Acc|Number=Plur|Person=1|PronType=Prs|Reflex=Yes	7	obl:arg	_	AlignBegin=65644|AlignEnd=66032|Gloss=ACC.PL.1.REFL
11	//	//	X	_	_	3	dep	_	AlignBegin=66032|AlignEnd=66032|Gloss=PUNCT

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 obj:lvc	color:blue
1	#	#	X	_	_	10	dep	_	AlignBegin=57536|AlignEnd=58100|Gloss=PUNCT
2	and	and	CCONJ	_	_	10	discourse	_	AlignBegin=58100|AlignEnd=58345|Gloss=and
3	{	{	X	_	_	4	dep	_	AlignBegin=58345|AlignEnd=58345|Gloss=PUNCT
4	I	I	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	6	reparandum	_	AlignBegin=58345|AlignEnd=58564|Gloss=NOM.SG.1
5	||	||	X	_	_	6	dep	_	AlignBegin=58564|AlignEnd=58564|Gloss=PUNCT
6	I	I	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	10	nsubj	_	AlignBegin=58564|AlignEnd=58765|Gloss=NOM.SG.1
7	}	}	X	_	_	4	dep	_	AlignBegin=58765|AlignEnd=58765|Gloss=PUNCT
8	do	no	AUX	_	_	10	aux	_	AlignBegin=58765|AlignEnd=58930|Gloss=NEG|Scrap=Yes|SpaceAfter=No
9	n't	not	PART	_	Polarity=Neg	10	advmod	_	AlignBegin=58930|AlignEnd=59047|Gloss=NEG
10	do	do	VERB	_	_	0	root	_	AlignBegin=59047|AlignEnd=59386|Gloss=do
11	bad	bad	ADJ	_	_	10	obj:lvc	_	AlignBegin=59047|AlignEnd=59386|Gloss=bad
12	//+	//+	X	_	_	15	dep	_	AlignBegin=59300|AlignEnd=59300|Gloss=PUNCT
13	#	#	X	_	_	15	dep	_	AlignBegin=59386|AlignEnd=59456|Gloss=PUNCT
14	for	for	ADP	_	_	15	case	_	AlignBegin=59456|AlignEnd=59717|Gloss=for
15	school	school	NOUN	_	_	10	obl:arg	_	AlignBegin=59456|AlignEnd=59717|Gloss=school
16	//	//	X	_	_	10	dep	_	AlignBegin=59717|AlignEnd=59717|Gloss=PUNCT

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 10 obj:lvc	color:blue
1	to	to	ADP	_	_	2	case	_	AlignBegin=62052|AlignEnd=62403|Gloss=to
2	me	me	PRON	_	Case=Acc|Number=Sing|Person=1|PronType=Prs	7	dislocated	_	AlignBegin=62403|AlignEnd=62754|Gloss=ACC.SG.1
3	ma	ma	PART	_	PartType=Disc	2	advmod	_	AlignBegin=62754|AlignEnd=63106|Gloss=FOC
4	<	<	X	_	_	2	dep	_	AlignBegin=63106|AlignEnd=63106|Gloss=PUNCT
5	I	I	PRON	_	Case=Nom|Number=Sing|Person=1|PronType=Prs	7	nsubj	_	AlignBegin=63106|AlignEnd=63457|Gloss=NOM.SG.1
6	no	no	AUX	_	Polarity=Neg	7	aux	_	AlignBegin=63457|AlignEnd=63808|Gloss=NEG
7	ready	ready	ADJ	_	ExtPos=VERB	0	root	_	AlignBegin=63808|AlignEnd=64159|Gloss=ready
8	to	to	ADP	_	_	9	mark	_	AlignBegin=64159|AlignEnd=64510|Gloss=to
9	do	do	VERB	_	_	7	ccomp	_	AlignBegin=64510|AlignEnd=64862|Gloss=do
10	falla	follow	VERB	_	_	9	obj:lvc	_	AlignBegin=64862|AlignEnd=65213|Gloss=follow
11	follow	follow	VERB	_	_	10	compound:svc	_	AlignBegin=65213|AlignEnd=65564|Gloss=follow
12	//	//	X	_	_	7	dep	_	AlignBegin=65564|AlignEnd=65564|Gloss=PUNCT

~~~


