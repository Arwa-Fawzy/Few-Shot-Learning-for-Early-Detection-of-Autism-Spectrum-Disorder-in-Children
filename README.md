# Few-Shot-Learning-for-Early-Detection-of-Autism-Spectrum-Disorder-in-Children
This repo contains the computational trials of the research paper titled: Few-Shot Learning for Early Detection of Autism Spectrum Disorder in Children 

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Dataset](#dataset)
- [Model](#model)
- [Results](#results)
- [Future Plans](#future-plans)
- [Publication](#publication)

## Introduction

Autism Spectrum Disorder (ASD) is a developmental condition affecting communication, behavior, and social interactions, characterized by a range of symptoms and severity levels where early detection and intervention are crucial for effective support. Acquiring labeled data is challenging due to high costs, specialized knowledge, or sample scarcity, especially in 'rare conditions' like 'childhood ASD'. 
We utilized few-shot learning (FSL) which is a machine-learning technique that trains the models by meta-learning with a minimal amount of labeled data, often just a few examples for each class.

## Features

- Few-shot learning for handling limited labeled data.
- Pre-trained backbone model for feature extraction.
- Minimizing processing Time.
- High accuracy in autism detection from children's images.

## Installation

### Install Dependencies
```bash
pip install -r requirements.txt
```
### Clone the Repository

```bash
  git clone https://github.com/Arwa-Fawzy/Few-Shot-Learning-for-Early-Diagnosis-of-Autism-Spectrum-Disorder-in-Children.git
  cd Few-Shot-Learning-for-Early-Diagnosis-of-Autism-Spectrum-Disorder-in-Children
```
## Dataset

In our FSL model, a labeled 'support set' S = {(x_i, y_i)} for i = 0 to N * K comprises approximately 3000 images from a public kaggle dataset [Autistic Children Facial Data Set](https://www.kaggle.com/datasets/imrankhan77/autistic-children-facial-data-set). , simulating a catalog or primary training data, alongside a 'query set' ($\mathcal{Q}=\{(x_i, y_i)\}_{i=0}^{M}$) resembling testing data, and 'episodes or tasks' that are equivalent to epochs. Each image in the query set requires classification using labels provided in the support set. Figure Shown illustrates a '2-way, 4-shots' with '10 query' instances of the classification task, where '2-way' denotes two distinct classes (autistic and non-autistic) and '4-shots' signifies four instances per class for each episodic training.

<img src="https://github.com/user-attachments/assets/0dd29aad-ad26-4f49-81d0-3c5fe75c053c" width="500">
<br>
<img src="https://github.com/user-attachments/assets/b60ce155-5b46-4062-9349-020541b1ad36" width="500">



## Model

## Results

## Future Plans

## Publication


