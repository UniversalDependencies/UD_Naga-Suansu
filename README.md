# Summary

UD_Naga-Suansu is a Universal Dependencies (UD) treebank for Suansu (Glottocode: suan1234), an endangered Tibeto-Burman language spoken on the Indo-Myanmar border. The annotation was performed manually based on glosses. This treebank includes texts from fiction and grammar. The treebank contains **3.1k** tokens, distributed as follows:

- **Training set**: 2945 tokens
- **Test set**: 157 tokens

# Introduction

The UD\_Naga-Suansu treebank consists of various texts translated into Suansu by native speakers, then glossed and annotated. The included texts are:

- **grammar\_Cairo**: 20 examples from the [Cairo Cicling Corpus]\([https://github.com/UniversalDependencies/cairo/blob/master/translations.txt](https://github.com/UniversalDependencies/cairo/blob/master/translations.txt))
- **grammar\_BivalTyp**: [BivalTyp](https\://www\.bivaltyp.info) dataset translated to Suansu.
- **grammar\_ValPal**: [ValPal](https://valpal.info) dataset dataset translated to Suansu.
- **film\_Bridge**: Begining of the subtitles from *Bridge of Spies* (2015).

## Genre Classification

- **Fiction**: Sentence IDs start with *film*.
- **Grammar**: Sentence IDs start with *grammar*.

## Data Splits

- **Training set**: Full **grammar\_Cairo**
- **Test set**: Full **grammar\_BivalTyp**, **grammar\_ValPal**, and **film\_Bridge**

# Acknowledgments

This work was supported by the University of Zurich Global Strategy and Partnerships Funding Scheme (Project Fund Level 3) (https://www.global.uzh.ch).
We gratefully acknowledge the Suansu-speaking community for their continuous support. We also thank Jason M. Vashum for his generous assistance with translation and annotation.

## References

* Say, Sergey (ed.). 2020-. BivalTyp: Typological database of bivalent verbs and their encoding frames. (Available online at https://www.bivaltyp.info, Accessed on 1 April 2025.)
* Hartmann, Iren & Haspelmath, Martin & Taylor, Bradley (eds.) 2013.
Valency Patterns Leipzig.
Leipzig: Max Planck Institute for Evolutionary Anthropology.
(Available online at https://valpal.info, Accessed on 2025-04-01.)


# Changelog

* 2025-05-15 v2.16
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.16
License: CC BY-SA 4.0
Includes text: yes
Genre: fiction grammar-examples
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Ivani, Jessica K.; Tulchynska, Kira
Contributing: here
Contact: jessica.ivani@uzh.ch; kira.tulchynska@mail.huji.ac.il
===============================================================================
</pre>
