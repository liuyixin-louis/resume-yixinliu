---
url_pdf: ""
date: 2021-07-04T02:16:21.016Z
summary: One software copyright, one set of software delivered to Southern Big
  Data Company
authors:
  - Yixin Liu
url_video: https://www.bilibili.com/video/BV185411574p?p=52
title: Automatic Extraction of Money Entity for Judgment Text
featured: true
tags:
  - Data Mining
external_link: https://github.com/liuyixin-louis/chip2020_track4_lyx
url_slides: project/chip2020/slide_chip2020.pdf
links: []
image:
  caption: ""
  focal_point: Smart
  filename: feature.png
  preview_only: true
url_code: https://github.com/liuyixin-louis/chip2020_track4_lyx
---
<!--StartFragment-->

<!--StartFragment-->

In actual legal business requirements, the extraction of the principal, interest and other amount fields in the legal loan judgment document is usually completed manually, which is time-consuming and labor-intensive. This project combines NLP technology to propose a BERT-based legal loan judgment document amount entity extraction model to realize the automatic extraction of ten types of amount entities.

<!--EndFragment-->

Our work:

1. Design the TF-IDF+Naive Bayes classification scheme to realize the preliminary screening of the judgment text and improve the processing efficiency.
2. Regular expressions are used to extract the amount entities; for the extracted amount entities, classification features are constructed according to their context, and BERT + logistic regression is used to complete the classification of the amount entity categories. After the model is tuned, the weighted accuracy rate reaches 93.5%;
3. Test and deployment, complete the module test with the person in charge of Party A, package the algorithm as docker and deploy to the server.

<!--EndFragment-->