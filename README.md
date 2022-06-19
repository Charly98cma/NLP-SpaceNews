# NLP-SpaceNews
## Introduction

NLP project of the subject *Intelligent Systems*, part of the *Master Universitario en Ingeniería Informática*, that uses the [Space News data set](https://www.kaggle.com/datasets/patrickfleith/space-news-dataset), which contains more than 17.000 articles related to the space industry covering news, commercial, civil, launches, military, and also opinion articles, to find the keywords of each article.

This articles are not classified based on their topic and do not give a small list of keywords to the reader, so we try to solve that on this project.

## Experiments

We have performed a series of operations to clean the text and check its properly encoded, normalized, etc. to find the most frequent words and find the keywords of each article using **T**erm **F**requency and **I**nverse **D**ocument **F**requency techniques.

## Run code

The file [scapenews-classifier.Rmd](https://github.com/Charly98cma/NLP-SpaceNews/blob/main/spacenews-classifier.Rmd) contains the code and a brief analysis of each operation, which can be executed using RStudio.

The file [archive.zip](https://github.com/Charly98cma/NLP-SpaceNews/blob/main/archive.zip) contains the data set in ZIP format, which **does not require manual unzip**, since the code already does that.