---
layout: relation
title: 'vocative'
shortdef: 'vocative'
udver: '2'
---

The <code>vocative</code> relation is used to mark a dialogue participant addressed in a text (common in conversations, dialogue, emails, newsgroup postings, etc.). Elements that can assume the role of <code>vocative</code> have the feature <code>Case</code> defined as <code>Voc</code>.

The relation links the addressee or the addressee’s name to its host sentence.

~~~ sdparse
შვილო, ის წიგნი მომიტანე. \n 'Child, bring me that book.'
vocative(მომიტანე, შვილო)
~~~
~~~ sdparse
მარიამ, დღეს რა გეგმები გაქვს? \n 'Maria, what plans do you have for today?'
vocative(გაქვს, მარიამ)
~~~

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:11:29 CET -->
