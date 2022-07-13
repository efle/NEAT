# Narrative Elements AnnoTation
This directory contains the dataset introduced in [Detecting Narrative Elements in Informational Text](https://aclanthology.org/2022.findings-naacl.133/). The dataset is divided into the train, validation and test sets which were used in the paper (for reproducibility purposes). 

The files are formatted as follows. Each line contains five tab-separated fields:
1. A sentence
2. An indication of whether or not the sentence contains a **Complication** (1 for yes, 0 for no)
3. An indication of whether or not the sentence contains a **Resolution** (1 for yes, 0 for no)
4. An indication of whether or not the sentence contains a **Success** (1 for yes, 0 for no)
5. The *domain category* of the article from which the sentence was taken

For more details, please refer to the paper.

If you use NEAT in your research, we would appreciate using the following to cite our paper:
```
@inproceedings{levi-etal-2022-detecting,
   title = "Detecting Narrative Elements in Informational Text",
   author = "Levi, Effi  and
     Mor, Guy  and
     Sheafer, Tamir  and
     Shenhav, Shaul",
   booktitle = "Findings of the Association for Computational Linguistics: NAACL 2022",
   month = jul,
   year = "2022",
   address = "Seattle, United States",
   publisher = "Association for Computational Linguistics",
   url = "https://aclanthology.org/2022.findings-naacl.133",
   pages = "1755--1765",
   abstract = "Automatic extraction of narrative elements from text, combining narrative theories with computational models, has been receiving increasing attention over the last few years. Previous works have utilized the oral narrative theory by Labov and Waletzky to identify various narrative elements in personal stories texts. Instead, we direct our focus to informational texts, specifically news stories. We introduce NEAT (Narrative Elements AnnoTation) {--} a novel NLP task for detecting narrative elements in raw text. For this purpose, we designed a new multi-label narrative annotation scheme, better suited for informational text (e.g. news media), by adapting elements from the narrative theory of Labov and Waletzky (Complication and Resolution) and adding a new narrative element of our own (Success). We then used this scheme to annotate a new dataset of 2,209 sentences, compiled from 46 news articles from various category domains. We trained a number of supervised models in several different setups over the annotated dataset to identify the different narrative elements, achieving an average $F_1$ score of up to 0.77. The results demonstrate the holistic nature of our annotation scheme as well as its robustness to domain category.",
}
```
