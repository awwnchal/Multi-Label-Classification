# Multi-Label-Classification

Toxic Comments Classification
- A Complete End-to-End Machine Learning project to classify a comment into various levels of toxicity

# Business Problem:
Toxic Comment Classification is a Kaggle competition held by the Conversation AI team, a research initiative founded by Jigsaw and Google.  In most of the online conversation platforms, social media users often face abuse, harassment, insult from other users. Due to which, many users stop expressing their ideas and opinions. Platforms struggle to facilitate conversations effectively. 

# Use of Machine Learning to solve the problem:
With all the latest advancements of AI-ML, the task is to build a efficient model that is capable of detecting various levels/categories of toxicity like threats, obscenity, insults, and identity-based hate for a given comment. Thus helping online conversations/discussion become more productive and respectful.

The problem at hand is not a multi-class classification, but it is a multi-label classification. In other words, a given comment may belongs to none or many levels of toxicity.

# Dataset Overview
Disclaimer : the dataset contains text that may be considered profane, vulgar, or offensive.
Dataset is available in the Kaggle competition page.
There are 3 files provided in the competition, viz. train, test, sample submission all in CSV format.
Train dataset contains large number of Wikipedia comments and its corresponding class labels encoded in binary format.
Levels of toxicity i.e. class labels are toxic, severe_toxic, obscene, threat, insult, identity_hate.
Like any machine learning classification task, test dataset contains only inputs (comments in this case) , for which toxicity probabilities need to predicted with the help of model trained on train dataset.
