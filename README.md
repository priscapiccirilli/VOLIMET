# VOLIMET

This repository contains the data collected as part of the VOLIMET dataset, presented in the paper [VOLIMET: A Parallel Corpus of Literal and Metaphorical Verb-Object Pairs for English–German and English–French](https://aclanthology.org/2024.starsem-1.18/), published at *SEM 2024.

The repository contains four folders: 

### en-source

Contains **source English sentences** extracted from Europarl, containing **literal** verb-objects, e.g., _address question_ (lit folder) and **metaphorical** verb-objects, e.g., _tackle question_ (met folder). <br/>
- *onlykeep.tsv files contain the full sentences with their respective verb-object and their inflection. <br/>
- *allinfo.tsv files list all verb-objects that were found in the sentences, the number of sentences containing those verb-objects, and the different inflections of the verb-objects. 

### en2de and en2fr

These folders contain the **source English sentences** containing **literal/metaphorical** (lit/met folders) verb-objects and their human-produced **German/French translations** extracted from Europarl. <br/>
- *onlykeep.tsv files contain the English sentences, which verb-object and its inflection can be found in the respective sentences, its German/French translated sentence. Additionally, we provide gold standard alignments of the English verb-objects with their corresponding translations in the target languages. <br/>
- *allinfo.tsv files contain all information across verb-objects: the number of sentences containing those verb-objects, their different inflections, their corresponding alignments and translations, as well as majority human judgements regarding the figurativeness of the corresponding translations.

We also provide human judgements regarding figurativeness of the translated literal/metaphorical verb-objects:<br/>
- main tsv file containing the majority judgement<br/>
- the individual judgement files (individual-judgements folder)

### guidelines

This folder contains:
- The guidelines for properly aligning English verb-objects to their respective German and French translations.
- The guidelines provided to expert annotators for judging whether phrases in the target languages are figurative or literal.

### Citation

If you use the VOLIMET dataset, please cite the following publication:
```bibtex
@inproceedings{piccirilli-etal-2024-volimet,
    title = "{VOLIMET}: A Parallel Corpus of Literal and Metaphorical Verb-Object Pairs for {E}nglish{--}{G}erman and {E}nglish{--}{F}rench",
    author = "Piccirilli, Prisca  and
      Fraser, Alexander  and
      Schulte im Walde, Sabine",
    editor = "Bollegala, Danushka  and
      Shwartz, Vered",
    booktitle = "Proceedings of the 13th Joint Conference on Lexical and Computational Semantics (*SEM 2024)",
    month = jun,
    year = "2024",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.starsem-1.18",
    doi = "10.18653/v1/2024.starsem-1.18",
    pages = "222--237",
}
```
