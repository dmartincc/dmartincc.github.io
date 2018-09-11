---
layout: post
toc: true
title:  "The 8 points you must follow to improve your machine learning classifiers"
date:   2018-09-10 10:00:00 +0200
author: David
keywords: data, machine lerning
category: lab
image: /img/photo-1516981879613-9f5da904015f.jpeg
description: The training procedure is a key task of the whole process of predicting values from supervised classifiers. This means that when a classifier is trained, it predicts what it has been taught, therefore, the trained dataset must met quality, consistency and reliability.
intro: The training procedure is a key task of the whole process of predicting values from supervised classifiers. This means that when a classifier is trained, it predicts what it has been taught, therefore, the trained dataset must met quality, consistency and reliability.
---

## **Metrics**

A main part of the training and testing process of a classifier is to compute several metrics, such as the following:

**[Precision](https://en.wikipedia.org/wiki/Precision_and_recall)** is the fraction of retrieved documents that are [relevant](https://en.wikipedia.org/wiki/Relevance_%28information_retrieval%29) or is the probability that a (randomly selected) retrieved document is relevant to the query.

> *precision = ({ relevant documents } ∩ { retrieved documents }) / {retrieved documents }*

**[Recall](https://en.wikipedia.org/wiki/Precision_and_recall)** is the fraction of the documents that are relevant to the query that are successfully retrieved or is the probability that a (randomly selected) relevant document is retrieved in a search.
> *recall = ({ relevant documents } ∩ { retrieved documents }) / { relevant documents }*

**[F1-Score](https://en.wikipedia.org/wiki/F1_score)** combines precision and recall is the [harmonic mean](https://en.wikipedia.org/wiki/Harmonic_mean) of precision and recall.
> *F1 = 2 · precision · recall / (precision + recall)*

## **Methodology**

From my experience developing classifiers for multiple purposes, these are my advised points to follow:

**1. Identify what you want to predict**

* Label one document with just one class.

* Multilabel one document with several classes, with unlimited number of classes.

* Multiclass one document with a defined set of classes.

**2. Get sample data**

At least with 10K data points covering all possible predictions, however, it is recommended to get as much data as possible.

**3. Clean and transform your data to the desired format**

Get your features from your structured or unstructured data and set of labels associated to predictors.

**4. Supervised the learning/training of your model**

It is needed to human checked the data selected for training your model, for doing so, it is required to have a consistent idea of what you are classifying, this means that a convention should be made in terms of what each label/category means and what comprises.

*Example:*
> *Today I feel lucky for being alive, however, this disease is killing me slowly. Positive — Negative (Is it positive or negative? Very subjective)*
> *I feel great today Positive (Clearly positive)*
> *Yesterday, I ate too much pizza and my tummy hurts Negative (Clearly negative)*

**5. Train and test your model**

When a checked dataset is ready to be used, train your classifier with that dataset, and test it over subset of your whole dataset, avoiding overfitting, this means that the training and testing data set should not have the same documents (66% train — 33% test)

**6. Check the metrics from the previous step**

Make sure to have a F1 score which meets your expectations of quality. Have in mind that we are dealing with probabilistic models, which by no means, do not return deterministic results, so level of uncertainty should be expected.

**7. Deploy your model**

If the metrics meet the expected quality, deploy your models into production.

**8. Iterate between points 5 and 7**

Until you get a robust model with which your operations and data science team are comfortable with.

## **Crowdsourcing your training process**

When training and human reviewing of datasets, it is normal to have team in charge of doing this tasks, this might comprise several problems which are state in following points:

**1. Mind the tools that your team is using**

Make sure that the members of your team are using the same tools, in order to avoid mistakes. If you have capabilities for build an ad-hoc web tool for training your models, do it!, you will avoid mistakes in your models.

**2. Choose the right people for the job**

Training a supervised model can be very very very tedious, it is a repetitive task and also should be done with a lot of care, because a simple mistake is going to be represented in your future predictions.

**3. Allow external crowdsourced training process to users**

Enable to final users to give feedback on predictions, but be careful to the trolls, setup limits.

**4. Mechanical Turk**

If you have your pockets full of bucks, you can use Amazon Mechanical Turk, a convenient approach if what you are looking for is to have a trained dataset fast.

## **Conclusions**

When training classifiers, the following points should be taken into consideration:

1. Define what you want to predict

2. Get enough data that covers all possible cases

3. Define what each category means

4. Curate your dataset for training the classifier

5. Train and test your classifier, having into account precision, recall and f1-score