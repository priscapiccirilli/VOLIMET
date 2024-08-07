# VOLIMET

This repository contains the data collected as part of the VOLIMET dataset, presented in the paper [VOLIMET: A Parallel Corpus of Literal and Metaphorical Verb-Object Pairs for English–German and English–French](https://aclanthology.org/2024.starsem-1.18/), published at *SEM 2024.

The repository contains four folders: 

### en-source

Contains **source English sentences** from Europarl, containing **literal** verb-objects, e.g., _address question_ (lit folder) and **metaphorical** verb-objects, e.g., _tackle question_ (met folder). \
*onlykeep.tsv files contain the full source sentence with its respective verb-object. \
*allinfo.tsv files list all verb-objects that were contained in the English sentences, along with their different inflections and their numbers.

### en2de and en2fr


### guidelines


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
