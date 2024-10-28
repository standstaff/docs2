---
layout: base
title:  "Gwich'in UD"
udver: "2"
---

# UD for Gwich'in <span class="flagspan"><img class="flag" src="../../flags/svg/US-AK.svg" /></span> <span class="flagspan" style="padding-left:1em"><img class="flag" src="../../flags/svg/CA.svg" /></span>


## Tokenization and Word Segmentation

* In general, words are delimited by whitespace characters.

---
**Instruction**: Describe the general rules for delimiting words (for example, based on whitespace and punctuation) and exceptions to these rules. Specify whether words with spaces and/or multiword tokens occur. Include links to further language-specific documentation if available.

---

## Morphology

### Tags

* Gwich'in uses 15 universal POS categories, including:
  * ADJ _tsal_, _k'eejit_, _tthoo_, etc.
  * ADP _hàa_, _shàa_, _zhìt_, _shizhìt_, etc.  
  * ADV _gwintsàl_, _oondàk_, _yeendàk_, _dą̀į’_, etc.
  * CCONJ _hàa_, _ts'à'_, _gàa_
  * DET _yagha’_, _aii_, _zhìk_, _izhìk_, etc.
  * INTJ _Àąhą’_, etc.
  * NOUN _vadzaih_, _shidink’ee_, _shee’ii_, _kwaiitryah_, etc. 
  * NUM _ch’ìhłak_, _dǫǫ_, etc.
  * PART _nąįį_, _kwàa_ 
  * PRON _shįį_, _jidìi_, etc.
  * PROPN _Vashrąįį K'ǫǫ_, _Tsiigehtchic_, _Dr. Burke_, etc.
  * PUNCT _._, _?_, _,_, etc.
  * SCONJ _jì_, _geh’àn_, _aii_, etc.
  * VERB _ihtsàl_, _giyahąąh’yaa_, _vintł’ihihtin_, etc. 
  * X is used for three words that could not be determined
* ADJ is used for adjective enclitics following NOUN.
* Verbal adjectives are tagged as VERB.
* Free standing personal pronouns are rare in the data. There is only one instance of these (_shįį_).
* Interrogative pronouns are tagged PRON.
* All words that take verbal inflection are tagged as VERB. This includes words that in English would take AUX.
* PART is used for words that denote negation (_kwàa_) or plurality (_nąįį_). 

---
**Instruction**: Specify any unused tags. Explain what words are tagged as PART. Describe how the AUX-VERB and DET-PRON distinctions are drawn, and specify whether there are (de)verbal forms tagged as ADJ, ADV or NOUN. Include links to language-specific tag definitions if any.

---

### Features

*

---
**Instruction**: Describe inherent and inflectional features for major word classes (at least NOUN and VERB). Describe other noteworthy features. Include links to language-specific feature definitions if any.

---

## Syntax

*

---
**Instruction**: Give criteria for identifying core arguments (subjects and objects), and describe the range of copula constructions in nonverbal clauses. List all subtype relations used. Include links to language-specific relations definitions if any.

---

## Treebanks

There is [one](../treebanks/gwi-comparison.html) Gwichin UD treebank:

  * [Gwichin-TueCL](../treebanks/gwi_tuecl/index.html)

---
**Instruction**: Treebank-specific pages are generated automatically from the README file in the treebank repository and
from the data in the latest release. Link to the respective `*-index.html` page in the `treebanks` folder, using the language code
and the treebank code in the file name.

---
