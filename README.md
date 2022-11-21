# IR From Bag-of-words to BERT and Beyond through Practical Experiments

This is the official repository of "*IR From Bag-of-words to BERT and Beyond through Practical Experiments*", a Search Solutions 2022 full-day tutorial with [PyTerrier](https://github.com/terrier-org/pyterrier) search toolkit.

# About the tutorial

Advances from the natural language processing community have recently sparked a renaissance in the task of adhoc search. Particularly, large contextualized language modeling techniques, such as [BERT](https://en.wikipedia.org/wiki/BERT_(language_model)), have equipped ranking models with a far deeper understanding of language than the capabilities of previous bag-of-words ([BoW](https://en.wikipedia.org/wiki/Bag-of-words_model)) models. Applying these techniques to a new task is tricky, requiring knowledge of deep learning frameworks, and significant scripting and data munging. In this full-day tutorial, we build up from foundational retrieval principles to the latest neural ranking techniques. We provide background on classical (e.g., [BoW](https://en.wikipedia.org/wiki/Bag-of-words_model)), modern (e.g., [Learning to Rank](https://en.wikipedia.org/wiki/Learning_to_rank)) and contemporary (e.g., [BERT](https://en.wikipedia.org/wiki/BERT_(language_model)) search ranking and re-ranking techniques. Going further, we detail and demonstrate how these can be easily experimentally applied to new search tasks in a new declarative style of conducting experiments exemplified by the [PyTerrier](https://github.com/terrier-org/pyterrier) search toolkit.

This tutorial is interactive in nature for participants; it is broken into sessions, each of which mixes explanatory presentation with hands-on activities using prepared Jupyter notebooks running on the [Google Colab](https://colab.research.google.com/) platform.

At the end of the tutorial, participants will be comfortable accessing classical inverted index data structures, building declarative retrieval pipelines, and conducting experiments using state-of-the-art neural ranking models.

# Authors

* [Sean MacAvaney](https://macavaney.us), University of Glasgow, UK
* [Craig Macdonald](http://www.dcs.gla.ac.uk/~craigm/), University of Glasgow, UK
* [Nicola Tonellotto](http://tonellotto.github.io), University of Pisa, IT

# Contents

* Part 1: Classical IR: indexing, retrieval and evaluation; Modern Retrieval Architectures: PyTerrier data model and operators, towards re-rankers and learning-to-rank
  - [Slides](slides/part1.pdf)
  - [Notebook 1](notebooks/notebook1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook1.ipynb)
  - [Notebook 2](notebooks/notebook2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook2.ipynb)
* Part 2: Contemporary Retrieval Architectures: Neural re-rankers such as BERT, EPIC, ColBERT
  - [Slides](slides/part2.pdf)
  - [OpenNIR and monoT5 Notebook](notebooks/notebook3.1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook3.1.ipynb)
  - [ColBERT Re-Ranker Notebook](notebooks/notebook3.2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook3.2.ipynb)
* Part 3: Recent Advances beyond the classical inverted index: neural inverted index augmentation, nearest neighbor search, dense retrieval
  - [Slides](slides/part3.pdf)
  - [ANCE notebook](notebooks/notebook4_1.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook4_1.ipynb)
  - [ColBERT notebook](notebooks/notebook4_2.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/terrier-org/searchsolutions2022-tutorial/blob/main/notebooks/notebook4_2.ipynb)

# Useful Links

 - PyTerrier: [[Github](https://github.com/terrier-org/pyterrier)] [[Documentation](https://pyterrier.readthedocs.io/en/latest/)]
 - OpenNIR: [[Github](https://github.com/Georgetown-IR-Lab/OpenNIR)] [[Documentation](https://opennir.net/)]
 - PyTerrier_ColBERT: [[Github](https://github.com/terrierteam/pyterrier_colbert)]
 - PyTerrier_T5: [[Github](https://github.com/terrierteam/pyterrier_t5)]
 - PyTerrier_doc2query: [[Github](https://github.com/terrierteam/pyterrier_doc2query)]
 - PyTerrier_DeepCT: [[Github](https://github.com/terrierteam/pyterrier_deepct)]
 - PyTerrier_ANCE: [[Github](https://github.com/terrierteam/pyterrier_ance)]
 - PyTerrier_SPLADE: [[Github](https://github.com/cmacdonald/pyt_splade)]


# Citation Policy

If you make using of any of these slides, notebooks, or additional PyTerrier plugins, please cite our tutorial abstract:

```bibtex

@inproceedings{searchsolutions2022-tutorial-tut-bow2b,
  author = {MacAvaney, Sean and Macdonald, Craig and Tonellotto, Nicola},
  title = {IR From Bag-of-words to BERT and Beyond through Practical Experiments: An ECIR 2021 tutorial with PyTerrier and OpenNIR},
  booktitle = {Proceedings of the 43rd European Conference on Information Retrieval Research},
  year = {2021}
}

```
