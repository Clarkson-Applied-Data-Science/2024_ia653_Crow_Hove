# 2024_ia653_Crow_Hove

# Introduction

In this project, we employ natural language processing (NLP) techniques to develop a machine learning model capable of classifying text as either AI-generated or human-written. 

With the rise of AI-generated content across various domains, identifying the origin of text is increasingly important for ensuring transparency, credibility, and authenticity in media, education, and digital communication. 

By analyzing linguistic patterns and textual features characteristic of AI and human authorship, our goal is to create a reliable predictive model that can distinguish between the two.

# Dataset Description

The dataset used in this project is the "Training_Essay_Data" dataset, sourced from **Kaggle**, comprising both AI-generated and human-written texts for binary classification and natural language processing tasks. This data was compiled from multiple sources and cleaned to remove duplicates, resulting in high-quality data for distinguishing between human and AI-generated content.

This dataset includes approximately 28,000 entries, each representing a unique essay labeled as either AI-generated or human-written. 

The rows contain text data, with a binary label indicating the source of generation (1 for AI-generated, 0 for human-written). 

This label distribution shows that about **37.3%** of the entries are AI-generated, and the remaining **62.7%** are human-written, providing a balanced yet slightly human-skewed dataset.

Variables in the dataset:

- text: The content of the essay or text, with **27,340 unique entries.**
- generated: A binary label where **"1" signifies AI-generated text, and "0" represents human-written text.**

This dataset is formatted as a CSV file with a total size of 65.46 MB, suitable for large-scale natural language processing and machine learning applications.

![Dataset Image](Images/dataset.png)

