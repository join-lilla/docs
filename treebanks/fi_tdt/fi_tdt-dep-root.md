---
layout: base
title:  'Statistics of root in UD_Finnish-TDT'
udver: '2'
---

## Treebank Statistics: UD_Finnish-TDT: Relations: `root`

This relation is universal.

15136 nodes (7%) are attached to their parents as `root`.

15136 instances of `root` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.24702695560254.

The following 14 pairs of parts of speech are connected with `root`: -<tt><a href="fi_tdt-pos-VERB.html">VERB</a></tt> (10439; 69% instances), -<tt><a href="fi_tdt-pos-NOUN.html">NOUN</a></tt> (2705; 18% instances), -<tt><a href="fi_tdt-pos-ADJ.html">ADJ</a></tt> (1021; 7% instances), -<tt><a href="fi_tdt-pos-PRON.html">PRON</a></tt> (300; 2% instances), -<tt><a href="fi_tdt-pos-ADV.html">ADV</a></tt> (290; 2% instances), -<tt><a href="fi_tdt-pos-PROPN.html">PROPN</a></tt> (261; 2% instances), -<tt><a href="fi_tdt-pos-NUM.html">NUM</a></tt> (49; 0% instances), -<tt><a href="fi_tdt-pos-INTJ.html">INTJ</a></tt> (31; 0% instances), -<tt><a href="fi_tdt-pos-X.html">X</a></tt> (12; 0% instances), -<tt><a href="fi_tdt-pos-SYM.html">SYM</a></tt> (11; 0% instances), -<tt><a href="fi_tdt-pos-AUX.html">AUX</a></tt> (8; 0% instances), -<tt><a href="fi_tdt-pos-ADP.html">ADP</a></tt> (4; 0% instances), -<tt><a href="fi_tdt-pos-CCONJ.html">CCONJ</a></tt> (3; 0% instances), -<tt><a href="fi_tdt-pos-SCONJ.html">SCONJ</a></tt> (2; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 1 root	color:blue
1	Saavuin	saapua	VERB	V	Mood=Ind|Number=Sing|Person=1|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
2	siis	siis	ADV	Adv	_	1	advmod	_	_
3	kaupunkiin	kaupunki	NOUN	N	Case=Ill|Number=Sing	1	obl	_	_
4	kameraryhmäni	kamera#ryhmä	NOUN	N	Case=Gen|Number=Sing|Number[psor]=Sing|Person[psor]=1	1	obl	_	_
5	kanssa	kanssa	ADP	Adp	AdpType=Post	4	case	_	_
6	jo	jo	ADV	Adv	_	8	advmod	_	_
7	ennen	ennen	ADP	Adp	AdpType=Prep	8	case	_	_
8	yhtätoista	yksi#toista	NUM	Num	Case=Par|Number=Sing|NumType=Card	1	obl	_	SpaceAfter=No
9	.	.	PUNCT	Punct	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 9 root	color:blue
1	Eräs	eräs	PRON	Pron	Case=Nom|Number=Sing|PronType=Ind	9	nsubj:cop	_	_
2	suosikkijutuistani	suosikki#juttu	NOUN	N	Case=Ela|Number=Plur|Number[psor]=Sing|Person[psor]=1	1	nmod	_	_
3	oli	olla	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	9	cop	_	_
4	tämä	tämä	PRON	Pron	Case=Nom|Number=Sing|PronType=Dem	9	det	_	_
5	vihreän	vihreä	ADJ	A	Case=Gen|Degree=Pos|Number=Sing	8	amod	_	_
6	ja	ja	CCONJ	C	_	7	cc	_	_
7	keltaisen	keltainen	ADJ	A	Case=Gen|Degree=Pos|Derivation=Inen|Number=Sing	5	conj	8:amod	_
8	värinen	värinen	ADJ	A	Case=Nom|Degree=Pos|Derivation=Inen|Number=Sing	9	amod	_	_
9	kesämekko	kesä#mekko	NOUN	N	Case=Nom|Number=Sing	0	root	_	SpaceAfter=No
10	.	.	PUNCT	Punct	_	9	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 0	bgColor:blue
# visual-style 0	fgColor:white
# visual-style 0 3 root	color:blue
1	On	olla	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	cop	_	_
2	kyllä	kyllä	ADV	Adv	_	3	advmod	_	_
3	kiva	kiva	ADJ	A	Case=Nom|Degree=Pos|Number=Sing	0	root	_	SpaceAfter=No
4	,	,	PUNCT	Punct	_	7	punct	_	_
5	kun	kun	SCONJ	C	_	7	mark	_	_
6	tuolla	tuolla	ADV	Adv	_	7	advmod	_	_
7	sai	saada	VERB	V	Mood=Ind|Number=Sing|Person=0|Tense=Past|VerbForm=Fin|Voice=Act	3	csubj:cop	_	_
8	hipelöidä	hipelöidä	VERB	V	InfForm=1|Number=Sing|VerbForm=Inf|Voice=Act	7	xcomp	_	_
9	kaikkea	kaikki	PRON	Pron	Case=Par|Number=Sing|PronType=Ind	8	obj	_	SpaceAfter=No
10	.	.	PUNCT	Punct	_	3	punct	_	SpaceAfter=No
11	:)	:)	SYM	Symb	_	3	discourse	_	_

~~~


