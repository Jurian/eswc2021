# Exploiting Transitivity for Entity Matching

The goal of entity matching in knowledge graphs is to identify sets of entities that refer to the same real-world object. Methods for entity matching in knowledge graphs, however, produce a collection of pairs of entities claimed to be duplicates. This collection that represents the sameAs relation may fail to satisfy some of its structural properties such as transitivity. We show that an ad-hoc enforcement of transitivity on the set of identified entity pairs may decrease precision. We therefore propose a methodology that starts with a given similarity measure, generates a set of entity pairs, and applies cluster editing to enforce transitivity, leading to overall improved performance.

## Overview
![flow](/img/eswc2021-flow2.png)

## Distribution of clusters in data
![cluster distributions](/img/cluster_size_distribution.jpg)

## F-0.5 Score
![f-0.5 score](/img/partial-ordered-5.50.lr.cos.100.fscore.jpg)

## Precision
![precision](/img/partial-ordered-5.50.lr.cos.100.precision.jpg)

## Linkset Size
![linkset size](/img/partial-ordered-5.50.lr.cos.100.size.jpg)

