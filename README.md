# CO490 Coursework: NLP Quality Estimation

## Team
* Anson Miu
* Cheryl Chen
* Clara Gila

## Introduction
Sentence-level quality estimation (QE) has emerged as a challenging task in natural langauge processing: 
given a source sentence and its machine translation (MT), the model should predict a score that expresses 
the quality of the translation (e.g. higher values indicate accurate translations).

We introduce four different methods for performing [sentence-level QE](https://competitions.codalab.org/competitions/22831) for pairs of source sentences and MT in 
English and Chinese respectively.

## Getting Started
Open `Sentence_Level_QE_2020.ipynb` on Google Colab and run the cells __in order__.

### Prerequisites
__Tested on Google Colab__

All required module/package dependencies, language models 
and data files will be downloaded in the notebook cells as required.

### Troubleshooting
* Make sure GPU is selected under _Runtime > Change runtime type_
* Restart the runtime and run the cells in order - the utility section contains functions used globally throughout the notebook
