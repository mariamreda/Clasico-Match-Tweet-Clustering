# Clasico Match Tweet Clustering

This project aims to cluster tweets collected during a Clasico match into sub-events using various clustering algorithms. Tweets are grouped based on similarities in text content and temporal closeness. The clustering algorithms applied include K-core clustering, k-truss clustering, Girvan-Newman algorithm, and Louvain community detection. The results are then analyzed and compared.

## Table of Contents

- [Introduction](#introduction)
- [Instructions](#instructions)
- [Dataset Description](#dataset-description)

## Introduction

The objective of this project is to cluster tweets collected during a Clasico match into sub-events, allowing for better understanding and analysis of the match dynamics. This involves preprocessing the tweet data, modeling tweets as a graph, applying various clustering algorithms, and analyzing the results.

## Instructions

1. **Data Cleaning**: Preprocess the tweet data to remove URLs, mentions, and non-alphabetic characters.
2. **Graph Modeling**: Model tweets as a graph where edges represent similarities based on text content and temporal closeness.
3. **Clustering Algorithms**:
   - Apply K-core clustering algorithm with K=5.
   - Apply k-truss clustering algorithm with a minimum common nodes between any two connected nodes = 3.
   - Apply Girvan-Newman algorithm.
   - Apply Louvain community detection.
4. **Analysis and Comparison**: Analyze the results of the clustering algorithms and compare their effectiveness in grouping tweets into sub-events.

## Dataset Description

The dataset is stored in the attached “Clasico.txt” file and consists of 1530 tweets collected during a Clasico match using the hashtag “#Clasico”. Each tweet is stored in the file in the following format: (TweetID$|Tweet_Text$|DateTime$|Location$$).


