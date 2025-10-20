# Amazon Fine Food Reviews Analysis

The project focuses on exploring the open **Amazon Fine Food Reviews** dataset from Kaggle.  
The main goal is to go through a complete machine learning workflow — from data analysis and cleaning to building basic models and evaluating their performance.  
This work was carried out as part of an academic research track in machine learning.

---

## Project Objectives

- Perform **Exploratory Data Analysis (EDA)**: study the distribution of ratings, review lengths, user activity, and other patterns.  
- Prepare the dataset for training — clean the text, normalize features, and remove noise.  
- Build and compare several **classical machine learning models** (logistic regression, decision tree, random forest, gradient boosting).  
- Evaluate model quality and determine which approaches predict review ratings most effectively.  
- Establish a foundation for future experiments in **Natural Language Processing (NLP)** and **Large Language Models (LLM)**.

---

## Dataset

The project uses the open [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews) dataset from Kaggle.  
It contains customer reviews of food products published on Amazon — including the full review text, a short summary, a numerical rating (1–5), and metadata such as user ID, product ID, and timestamp.

A sample of **50,000 reviews** was used for the analysis — this size is sufficient for meaningful EDA and model training on a regular laptop.

Main fields:
- `Text` — full review text  
- `Summary` — short description of the review  
- `Score` — rating (1–5)  
- `UserId`, `ProductId`, `ProfileName` — user and product identifiers  
- `Time` — review publication time

> **Data files aren't included in this repository.**  
> The dataset can be downloaded from Kaggle: [Amazon Fine Food Reviews](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews).

