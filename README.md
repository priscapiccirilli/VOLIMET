# VOLIMET

This repository contains the data collected as part of the VOLIMET dataset, presented in the paper [VOLIMET: A Parallel Corpus of Literal and Metaphorical Verb-Object Pairs for English–German and English–French](https://aclanthology.org/2024.starsem-1.18/), published at *SEM 2024.

The repository contains four folders: 

### en-source

Contains **source English sentences** extracted from Europarl, containing **literal** verb-objects, e.g., _address question_ (lit folder) and **metaphorical** verb-objects, e.g., _tackle question_ (met folder). <br/>
- *onlykeep.tsv files contain the full source sentences with their respective verb-object. <br/>
- *allinfo.tsv files list all verb-objects that were found in the English sentences, the number of sentences containing those verb-objects, and the different inflections of the verb-objects. 
### en2de and en2fr

These folders contain the **source literal/metaphorical** (lit/met folders) **English sentences** and their **German/French translations**.<br/>
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
