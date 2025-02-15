---
layout: feature
title: 'Animacy'
shortdef: 'animacy'
udver: '2'
---

<table class="typeindex" border="1">
<tr>
  <td style="background-color:cornflowerblue;color:white"><strong>Values:</strong> </td>
  <td><a href="#Anim">Anim</a></td>
  <td><a href="#Inan">Inan</a></td>
</tr>
</table>

Similarly to [Gender](), animacy is a lexical feature of [nouns](cs-pos/NOUN)
and inflectional feature of other parts of speech that mark agreement with
nouns. It is cross-linguistically independent of gender, therefore it is
encoded as a separate feature in UD and also in some Czech tagsets
(e.g. Multext-East). On the other hand, in Czech the (almost) only grammatical
implications occur within the masculine gender, which is why the PDT tagset
does not have animacy as separate feature and instead defines four genders:
masculine animate, masculine inanimate, feminine and neuter.

The following table demonstrates how masculine animate vs. inanimate inflection
differs in singular genitive, dative, accusative and locative, and plural
nominative/vocative. The differences are also projected to congruent adjectives
and determiners; plural nominative is also projected to predicative participles
(_pánové zvítězili_ “gentlemen won” vs. _vozy zvítězily_ “cars won”).

<table>
<tr><td></td><td><tt>Masc Anim</tt></td><td><tt>Masc Inan</tt></td></tr>
<tr><td></td><td>“this strong gentleman”</td><td>“this strong car”</td></tr>
<tr><td><tt>Sing Nom &nbsp;</tt></td><td><i>tento silný pán</i></td><td><i>tento silný vůz</i></td></tr>
<tr><td><tt>Sing Gen &nbsp;</tt></td><td><i>tohoto silného pán<span style="color:red">a</span></i></td><td><i>tohoto silného voz<span style="color:red">u</span></i></td></tr>
<tr><td><tt>Sing Dat &nbsp;</tt></td><td><i>tomuto silnému pán<span style="color:red">ovi</span>/pánu</i></td><td><i>tomuto silnému vozu</i></td></tr>
<tr><td><tt>Sing Acc &nbsp;</tt></td><td><i>t<span style="color:red">oho</span>to siln<span style="color:red">ého</span> pán<span style="color:red">a</span></i></td><td><i>t<span style="color:red">en</span>to siln<span style="color:red">ý</span> vůz</i></td></tr>
<tr><td><tt>Sing Voc &nbsp;</tt></td><td><i>silný pane</i></td><td><i>silný voze</i></td></tr>
<tr><td><tt>Sing Loc &nbsp;</tt></td><td><i>tomto silném pán<span style="color:red">ovi</span>/pánu</i></td><td><i>tomto silném vozu/voz<span style="color:red">e</span></i></td></tr>
<tr><td><tt>Sing Ins &nbsp;</tt></td><td><i>tímto silným pánem</i></td><td><i>tímto silným vozem</i></td></tr>
<tr><td><tt>Plur Nom &nbsp;</tt></td><td><i>t<span style="color:red">i</span>to siln<span style="color:red">í</span> pán<span style="color:red">ové</span>/pán<span style="color:red">i</span></i></td><td><i>t<span style="color:red">y</span>to siln<span style="color:red">é</span> voz<span style="color:red">y</span></i></td></tr>
<tr><td><tt>Plur Gen &nbsp;</tt></td><td><i>těchto silných pánů</i></td><td><i>těchto silných vozů</i></td></tr>
<tr><td><tt>Plur Dat &nbsp;</tt></td><td><i>těmto silným pánům</i></td><td><i>těmto silným vozům</i></td></tr>
<tr><td><tt>Plur Acc &nbsp;</tt></td><td><i>tyto silné pány</i></td><td><i>tyto silné vozy</i></td></tr>
<tr><td><tt>Plur Voc &nbsp;</tt></td><td><i>siln<span style="color:red">í</span> pán<span style="color:red">ové</span>/pán<span style="color:red">i</span></i></td><td><i>siln<span style="color:red">é</span> voz<span style="color:red">y</span></i></td></tr>
<tr><td><tt>Plur Loc &nbsp;</tt></td><td><i>těchto silných pánech</i></td><td><i>těchto silných vozech</i></td></tr>
<tr><td><tt>Plur Ins &nbsp;</tt></td><td><i>těmito silnými pány</i></td><td><i>těmito silnými vozy</i></td></tr>
</table>

### <a name="Anim">`Anim`</a>: animate

Human beings, animals, fictional characters, names of professions
etc. are all animate. Even nouns that are normally inanimate can be
inflected as animate if they are personified. For instance, consider a
children's story about cars where cars live and talk as people; then
the cars may become and be inflected as animates.

Furthermore, some car brand/model names can in some cases take
animate inflections (in any genre, not just children's stories),
despite being semantically inanimate. This is a mixed paradigm:
The animate inflection (including adjective/determiner agreement)
can be used in singular but not in plural, and even in singular
it still alternates with the inanimate inflection:
_Koupil si starého trabanta_ (animate) vs.
_Koupil si starý trabant_ (inanimate) “He bought an old Trabant.”

#### Examples

Examples of masculine animate nouns:

* _<b>člověk</b>&nbsp;_ “man”, _<b>ministr</b>&nbsp;_ “minister”, _<b>prezident</b>&nbsp;_ “president”, _<b>předseda</b>&nbsp;_ “chairman”, _<b>ředitel</b>&nbsp;_ “director”
* _<b>pes</b>&nbsp;_ “dog”, _<b>kůň</b>&nbsp;_ “horse”, _<b>vrabec</b>&nbsp;_ “sparrow”, _<b>krokodýl</b>&nbsp;_ “crocodile”, _<b>kapr</b>&nbsp;_ “carp”

### <a name="Inan">`Inan`</a>: inanimate

Nouns that are not animate are inanimate.

#### Examples

Examples of masculine inanimate nouns:

* _<b>rok</b>&nbsp;_ “year”, _<b>zákon</b>&nbsp;_ “law”, _<b>stát</b>&nbsp;_ “state”, _<b>případ</b>&nbsp;_ “case”, _<b>milión</b>&nbsp;_ “million”
* _<b>smrk</b>&nbsp;_ “spruce”, _<b>dub</b>&nbsp;_ “oak”, _<b>buk</b>&nbsp;_ “beech”, _<b>heřmánek</b>&nbsp;_ “camomile”, _<b>hřib</b>&nbsp;_ “bolete”

<!-- Interlanguage links updated Po 11. listopadu 2024, 20:09:31 CET -->
