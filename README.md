# Automatically Creating a Lexicon of Verbal Polarity Shifters: Mono- and Cross-lingual Methods for German
This repository contains the data created as part of:

[Marc Schulder](http://marc.schulder.info), [Michael Wiegand](http://www.coli.uni-saarland.de/~miwieg/), [Josef Ruppenhofer](http://ruppenhofer.de/) (2017). **"Automatically Creating a Lexicon of Verbal Polarity Shifters: Mono- and Cross-lingual Methods for German"**. Proceedings of the 27th International Conference on Computational Linguistics (COLING 2018). Santa Fe, New Mexico, USA, August 20 - August 26, 2018.

[PDF](http://marc.schulder.info/data/SchulderWiegandRuppenhofer2018.pdf)

## Content
We provide a bootstrapped lexicon of German verbal polarity shifters.
Our lexicon covers 2595 verbs of GermaNet (Hamp and Feldweg, 1997).
Polarity shifter labels are given for each word lemma.
All labels were assigned by an expert annotator who is a native speaker of German.

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
  author={Schulder, Marc and Wiegand, Michael and Ruppenhofer, Jose},
  booktitle={Proceedings of the 27th International Conference on Computational Linguistics},
  year={2018},
  publisher={International Committee on Computational Linguistics},
  volume={1},
  address={Santa Fe, New Mexico, USA},
}
```

## Acknowledgements
This work was partially supported by the German Research Foundation (DFG) under grants RU 1873/2-1 and WI4204/2-1.

## References
Birgit Hamp and Helmut Feldweg. 1997. GermaNet - a Lexical-Semantic Net for German. In "Proceedings of ACL Workshop Automatic Information Extraction and Building of Lexical Semantic Resources for NLP Applications", pages 9–15, Madrid, Spain.
