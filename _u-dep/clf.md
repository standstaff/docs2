---
layout: relation
title: 'clf'
shortdef: 'classifier'
udver: '2'
---

A `clf` (classifier) is a word which accompanies a noun in certain grammatical contexts.
The most canonical use is numeral classifiers, where the word is used with a number for counting objects.
A classifier generally reflects some kind of
conceptual classification of nouns, based principally on features of their referents.
Etymologically, classifiers are normally historically nouns, and the words may still also be used as independent nouns,
but in their classifier use they have scant semantics left.
In most cases, the most appropriate UPOS to give classifiers will still be NOUN, though you may wish to give the words a feature
indicating their special status as a classifier. (There is at present no Universal feature for classifiers, but `NounType=Clf`
might be apt.)
The `clf` function is intended for languages which have highly grammaticalized systems of classifiers.
The greatest density of such languages is in Asia.
As well as core classifiers, there are often also other words, sometimes called "massifiers" that are used in counting with
similar behavior to classifiers. These typically include words for containers ("cup", "box") and units ("month", "inch"),
such as Chinese 袋 ‘bag’ in 一袋米 [one bag rice] ‘a bag of rice’.
In a classifier language, it is usually most appropriate to also analyze these words as classifiers.
Most other languages also count things with units, however, for these languages, such as English, `clf` is not used and rather
standard noun phrase relations are still used (despite there also being incipient grammaticalization in many cases, including English).
See the examples for English at the end.

Here are some examples from Mandarin/Putonghua Chinese:

* 三个学生 (三個學生) sān gè xuéshēng = “three students”, literally “three [human-classifier] student”
* 三棵树 (三棵樹) sān kē shù = “three trees”, literally “three [tree-classifier] tree”
* 三只鸟 (三隻鳥) sān zhī niǎo = “three birds”, literally “three [bird-classifier] bird”
* 三条河 (三條河) sān tiáo hé = “three rivers”, literally “three [long-wavy-classifier] river”

Analogous examples from Thai:

* นักเรียนสามคน nâkríán sám gʰn = “three students”, literally “student three [human-classifier]”
* ต้นไม้สามต้น t²nmai² sám t²n = “three trees”, literally “tree three [tree-classifier]”
* นกสามตัว nk sám túá = “three birds”, literally “bird three [animal-classifier]”
* แม่น้ำสามสาย mǽ¹nã² sám sáy = “three rivers”, literally “river three [river-classifier]”

Syntactically, the classifier groups with the numeral rather than the noun and we therefore treat
classifiers as functional dependents of numerals (or possessives) using the new `clf` relation. (This
is one of Greenberg’s universals and is true in almost all cases.
A couple of exceptions are noted in Aikhenvald (2000: 105) _Classifiers_, OUP, but it is noticeable that in those languages
the putative head noun is in the genitive case.)

~~~ sdparse
三/NUM 个/NOUN 学生/NOUN \n sān gè xuéshēng \n three CLF student
nummod(学生, 三)
clf(三, 个)
nummod(xuéshēng, sān)
clf(sān, gè)
nummod(student, three)
clf(three, CLF)
~~~

~~~ sdparse
แมว/NOUN สาม/NUM ตัว/NOUN \n mǽw sám túá \n cat three CLF
nummod(แมว, สาม)
clf(สาม, ตัว)
nummod(mǽw, sám)
clf(sám, túá)
nummod(cat, three)
clf(three, CLF)
~~~

Sometimes a classifier is inserted between a demonstrative and a noun (instead of numeral and noun) [zh]:

~~~ sdparse
乘坐 這 輛 巴士 \n Chéngzuò zhè liàng bāshì \n Take this CLF bus
obj(乘坐, 巴士)
det(巴士, 這)
clf(這, 輛)
obj(Chéngzuò, bāshì)
det(bāshì, zhè)
clf(zhè, liàng)
obj(Take, bus)
det(bus, this)
clf(this, CLF)
~~~

Classifier words also occur in various other constructions, and so it is important to distinguish the word in a particular
language from the universal classifier function proposed in UD. We go here through some further examples with Chinese classifiers.

The number and classifier may appear without the counted noun.
In this case, the classifier takes the role of the missing noun, and we promote the classifier to be the head.
So 我 買 兩 本 “I am buying two” is regarded as “I am buying two [books-CLF]”.

~~~ sdparse
我 買 兩 本 \n I buy two CLF
obj(買, 本)
nummod(本, 兩)
~~~

In some languages, including Chinese, a classifier can also appear without a number, and frequently then has some sort of
determinative function. We use the relation `det` for such uses of a classifier. For instance, in Cantonese ‘She bought a/the book’:

~~~ sdparse
佢 買 咗 本 書 \n keoi maai zo bun syu \n 3sg buy PERF CLF book
obj(買, 書)
det(書, 本)
~~~

For languages without highly grammaticalized classifier systems, standard nominal modification relationships are used
even when things are being counted in groups (with "massifiers"). For example, in English:

~~~ sdparse
three cups of rolled oats
nummod(cups, three)
case(oats, of)
amod(oats, rolled)
nmod(cups, oats)
~~~

~~~ sdparse
three cups rolled oats
nummod(cups, three)
amod(oats, rolled)
nmod(cups, oats)
~~~
<!-- Interlanguage links updated Po 11. listopadu 2024, 20:10:36 CET -->
