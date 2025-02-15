---
layout: feature
title: 'Tense'
shortdef: 'tense'
udver: '2'
---

In English, `Tense` is a feature of [verbs](en-pos/VERB) that specifies the time when the action took / takes / will take place, in relation to the current moment or to another action in the utterance.

Some English [tenses](Tense) are a combination of tense and aspect. But as the aspect always depends on the tense we mark (verbs)[en-pos/VERB] only with the [tense](Tense) feature.


### <a name="Pres">`Pres`</a>: present tense

The present tense denotes actions that are happening right now or that usually happen. All verbs with the PTB tag `VBP` or `VBZ` have this feature. [Subjunctives](Mood) with the PTB tag `VB` also have this feature.

#### Examples:

* _She <b>goes</b> home._
* _I suggest that he <b>see</b> a doctor._

### <a name="Past">`Past`</a>: past tense

The past tense denotes actions that happened before the current moment. All verbs with the PTB tag `VBD` and `VBN` have this feature.

#### Examples:

* _She <b>went</b> home._

Note that the pluperfect and future tenses in English are constructed periphrastically. For example, _I <b>had been</b> there_ is past perfect (pluperfect) tense, formed periphrastically by the simple past tense of the auxiliary _to have_ and the past participle of the main verb _to be_. The auxiliary will be tagged `VerbForm=Fin|Mood=Ind|Tense=Past` and the participle will have `VerbForm=Part|Tense=Past`; none of the two will have `Tense=Pqp`.
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:07 CET -->
