---
layout: relation
title: 'obj:ro'
shortdef: 'relational object'
udver: '2'
---

The `obj:ro` relation marks an an object referenced by a relational object marker.

~~~ conllu
# text = Аҵысҕра иаҳәаз ажәақәа иаарызхәыцит Абгахәыҷы.
# text-transcription = Ac̣əsγra iaḥʷaz ažʷakʷa iaarəzxʷəciṭ Abgaxʷəć̣ə.
# translation = The Fox thought about the words the Chaffinch had said. 
1       Аҵысҕра а-ҵы́сҕра        NOUN    Noun_NH_Sg_Det  Animacy=Nhum|Definite=Def|Number=Sing   2       nsubj   _       _
2       иаҳәаз  а-ҳәара́        VERB    V_Dyn_Tr_NonFin_PastIndef_S:3SgNH_DO:Rel_Rel    Dyn=Yes|Gender[subj]=Neut|Number[subj]=Sing|Person[obj]=Rel|Person[subj]=3|Tense=Past|Trans=Yes|VerbForm=NonFin 3       acl:relcl       _    \
   _
3       ажәақәа а́жәа    NOUN    Noun_NH_Pl_[Det]        Animacy=Nhum|Number=Plur        4       obj:ro  _       _
4       иаарызхәыцит    а-зхәы́цра     VERB    V_Dyn_Intr_Fin_Aor_FPv:аа_S:3_RO:3Pl_Reln:For   Dyn=Yes|Number[ro]=Plur|Person[ro]=3|Person[subj]=3|Reln=Ben|Tense=Aor|Trans=No|VerbForm=Fin    0       root    _       _
5       Абгахәыҷы       а-бгахәыҷы́      NOUN    Noun_NH_Sg_Det  Animacy=Nhum|Definite=Def|Number=Sing   4       nsubj   _       _
6       .       .       PUNCT   Punct_Period    _       4       punct   _       _
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:14 CET -->
