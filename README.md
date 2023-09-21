# <p align=center>Classification and Clustering of Sentence-Level Embeddings of Scientific Articles</p>

This repo has code and data for the paper titled Classification and Clustering of Sentence-Level Embeddings of Scientific Articles.

## Introduction

All codes are in Jupyter Notebook format.

## File and Directory Strucutre

1. DATASETS directory: holds CSAbstruct, PMC-Sents-FULL and PubMed_RCT datasets.
2. [\[1\] ST Embeddings Generation.ipynb]([1]%20ST%20Embeddings%20Generation.ipynb): code to generate the corresponding embeddings of CSAbstruct, PMC-Sents-FULL or PubMed_RCT datasets.
3. [\[2\] Classifiers Train and Testing.ipynb]([2]%20Classifiers%20Train%20and%20Testing.ipynb): code to train and test Decision Tree, KNN, MLP, Random Forest and SVM classifiers based on generated the embeddings of the previous step.
4. [\[3\] Test LM [CLS] Classifiers.ipynb]([3]%20Test%20LM%20[CLS]%20Classifiers.ipynb): code to test the fine-tuned SciBERT language models on CSAbstruct, PMC-Sents-FULL or PubMed_RCT datasets.
5. [\[4\] Clustering Results.ipynb]([4]%20Clustering%20Results.ipynb): clustering results based on the generated embeddings of step 1.
