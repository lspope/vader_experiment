# Comparing VADER to Human-labeled Sentiment


Prepared and presented by: [Leah Pope](https://www.linkedin.com/in/leahspope/) 

Blog: [Coming Soon!](https://lspope.github.io/)

![tweeting](images/tim-mossholder-lBNCfM_jsh8-unsplash.jpg)


# Introduction

The goal of this experiment is to compare human labeled sentiment (the gold standard) to [VADER (Valence Aware Dictionary and sEntiment Reasoner)](https://github.com/cjhutto/vaderSentiment) labeled sentiment for two similar sets of Tweets.

This is a follow-on from my [Flatiron Phase 4 Project](https://github.com/lspope/dsc-phase-4-project) where I built a text classifer to classify Tweets as either Positive, Negative, or Neutral. 


# Data
The datasets are from [CrowdFlower](https://data.world/crowdflower). I used the [Product Emotions](https://data.world/crowdflower/brands-and-product-emotions) and [Apple Tweets](https://data.world/crowdflower/apple-twitter-sentiment) dataset.



# Repository Structure
```
--notebooks
----data_cleaning.ipynb
----vader_comp.ipynb
--data (dir for all raw and processed data files)
--images (dir for images)
```