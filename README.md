# Bootstrapped Lexicon of German Verbal Polarity Shifters
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.3365369.svg)](https://doi.org/10.5281/zenodo.3365369)

This repository contains the data created as part of:

[Marc Schulder](http://marc.schulder.info), [Michael Wiegand](http://www.coli.uni-saarland.de/~miwieg/) and [Josef Ruppenhofer](http://ruppenhofer.de/) (2018). [**"Automatically Creating a Lexicon of Verbal Polarity Shifters: Mono- and Cross-lingual Methods for German"**](https://www.aclweb.org/anthology/C18-1213). _Proceedings of the 27th International Conference on Computational Linguistics (COLING 2018)_, pages 2516–2528, Santa Fe, New Mexico, USA, 20–26 August 2018.

## Content
We provide a bootstrapped lexicon of German verbal polarity shifters.
Our lexicon covers 2595 verbs of [GermaNet](http://www.sfs.uni-tuebingen.de/GermaNet/) (Hamp and Feldweg, 1997).
Polarity shifter labels are given for each word lemma.
All labels were assigned by an expert annotator who is a native speaker of German.

### Resources
- **Paper:** [ACL Anthology](https://www.aclweb.org/anthology/C18-1213)
- **Poster:** [Link](http://marc.schulder.info/files/posters/2018_07_bootstrapped-lexicon-of-german-verbal-polarity-shifters.pdf)
- **Data:** See content of this repository

#### Related Resources
- **[Polarity Shifter Resources](https://github.com/uds-lsv/polarity-shifter-resources)**
  - **[IJCNLP 2017](https://github.com/uds-lsv/bootstrapped-lexicon-of-english-verbal-polarity-shifters):** Lexicon of English Verbal Shifters (bootstrapped, lemma-level)
  - **[LREC 2018](https://github.com/uds-lsv/lexicon-of-english-verbal-polarity-shifters):** Lexicon of English Verbal Shifters (manual, sense-level)
  - **[LREC 2020](https://github.com/uds-lsv/lexicon-of-polarity-shifting-directions):** Lexicon of Polarity Shifting Directions (supervised classification, lemma-level).
  - **[JNLE 2020](https://github.com/uds-lsv/bootstrapped-lexicon-of-english-polarity-shifters):** General Lexicon of English Shifters (bootstrapped, lemma-level).
- **[Word Embedding of Amazon Product Review Corpus](https://doi.org/10.5281/zenodo.3370051):** Word2Vec word embedding used to create this data.
## Files
The data consists of two lists of GermaNet verbs (Hamp and Feldweg, 1997), annotated for whether they cause shifting:
1. `verbal_shifters.gold_standard.txt`: The initial gold standard (§3) of 2000 randomly sampled verbs.
2. `verbal_shifters.bootstrapping.txt`: The bootstrapped 595 verbs (§5.3) that were labelled as shifters by our best classifier and then manually annotated.

### Format
Each line contains a verb and its label, separate by a whitespace.

## Attribution
This data set is published under [Creative Commons Attribution 4.0](https://github.com/uds-lsv/bootstrapped-lexicon-of-german-verbal-polarity-shifters/blob/master/LICENSE).

If you use it in your research or work, please cite the publication (see above).

### BibTex
```
@inproceedings{schulder2018germanshifter,
  title={Automatically Creating a Lexicon of Verbal Polarity Shifters: Mono- and Cross-lingual Methods for German},
  author={Schulder, Marc and Wiegand, Michael and Ruppenhofer, Josef},
  booktitle={Proceedings of the 27th International Conference on Computational Linguistics},
  pages={2516--2528},
  year={2018},
  month = {August},
  date = {20-26},
  address={Santa Fe, New Mexico, USA},
  publisher={International Committee on Computational Linguistics},
  volume={1},
}
```

## Acknowledgements
This work was partially supported by the German Research Foundation (DFG) under grants RU 1873/2-1 and WI4204/2-1.

## References
Birgit Hamp and Helmut Feldweg. 1997. GermaNet - a Lexical-Semantic Net for German. In "Proceedings of ACL Workshop Automatic Information Extraction and Building of Lexical Semantic Resources for NLP Applications", pages 9–15, Madrid, Spain.
