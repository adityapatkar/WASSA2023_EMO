# RoBERTa-Based Emotion Classification of Essays: Improving Performance on Imbalanced Data

## Description
Code repository for the paper "Using RoBERTa for Emotion Classification of Essays: Insights into Handling Imbalanced Data" that explores the use of RoBERTa and various data balancing techniques for improving emotion classification performance on a benchmark dataset of essays.

This repository contains the code implementation for the paper titled "Using RoBERTa for Emotion Classification of Essays: Insights into Handling Imbalanced Data". The paper presents a study on using the RoBERTa language model for emotion classification of essays, as part of the Shared Task on Empathy Detection, Emotion Classification and Personality Detection in Interactions, organized as part of WASSA 2023 at ACL 2023. The study explores the use of various data balancing techniques in combination with RoBERTa to improve the classification performance. The code implementation includes pre-processing, training, and evaluation of the proposed approach on a benchmark multi-label dataset of essays annotated with eight emotion categories provided by the Shared Task organizers. The repository also contains the necessary files for reproducing the results reported in the paper. Our approach was ranked first in the shared task.

## Content:

The repository includes the following files:

1. Wassa_2023_Shared_Task_EMO_EDA.ipynb: This file contains the code related to the exploratory data analysis and the training of the baseline.

2. Wassa_2023_Shared_Task_EMO_Training.ipynb: This file contains the code related to the training of the model.

## Other Resources
1. https://huggingface.co/adityapatkar/WASSA_EMO contains the pre-trained final model. (Currently a private repo, will be made public in due course)
2. https://codalab.lisn.upsaclay.fr/competitions/11167#learn_the_details-datasets contains the datasets used for this task.
