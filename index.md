# Exploiting Transitivity for Entity Matching

The goal of entity matching in knowledge graphs is to identify sets of entities that refer to the same real-world object. Methods for entity matching in knowledge graphs, however, produce a collection of pairs of entities claimed to be duplicates. This collection that represents the sameAs relation may fail to satisfy some of its structural properties such as transitivity. We show that an ad-hoc enforcement of transitivity on the set of identified entity pairs may decrease precision. We therefore propose a methodology that starts with a given similarity measure, generates a set of entity pairs, and applies cluster editing to enforce transitivity, leading to overall improved performance.

## Overview
![flow](/img/eswc2021-flow2.png)

## Generate random clusters with different sizes
![cluster distributions](/img/cluster_size_distribution.jpg)

## Improve F-0.5 score over a range of cutoff values
Feature: Cosine Similarity | Features: Hadamard Product
:---: | :---:
![f-0.5 score](/img/partial-ordered-5.50.lr.cos.100.fscore.jpg) | ![f-0.5 score](/img/partial-ordered-5.10.lr.had.300.fscore.jpg)
**Logistic Regression** | **Logistic Regression**
![f-0.5 score](/img/partial-ordered-5.10.svm.cos.100.fscore.jpg) | ![f-0.5 score](/img/partial-ordered-5.25.svm.had.300.fscore.jpg)
**SVM** | **SVM**

## Precision
![precision](/img/partial-ordered-5.50.lr.cos.100.precision.jpg)

## Linkset Size
![linkset size](/img/partial-ordered-5.50.lr.cos.100.size.jpg)

