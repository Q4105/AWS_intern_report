---
title: "Worklog Week 11"
date: 2026-07-13
weight: 11
chapter: false
pre: " <b> 1.11. </b> "
---

### Week 11: Dataset search, cleaning, model training and UI prototype

**Duration:** 20/07/2026 – 26/07/2026

#### Goals

* Find and select the best dataset for the team project
* Clean and prepare the dataset for model training
* Start the UI prototype for the demo site

#### Work performed

* Researched possible datasets for Vietnamese toxic text and chose a reliable corpus, then downloaded and inspected the dataset structure, labels, and format
* Built data-cleaning scripts to normalize Vietnamese text, remove duplicates, filter noise, and fix label inconsistencies
* Prepared training, validation, and test splits with consistent preprocessing rules for text normalization and tokenization
* Set up the training environment in Google Colab, trained an initial model on the cleaned dataset, and tracked the first evaluation metrics
* Designed the demo UI flow in React, created the input form and result display components, and defined the integration contract for the backend API

#### Results

* a cleaned dataset ready for model training, with preprocessing code documented in the repository
* A first training run completed and the model ready for further tuning
* A UI prototype ready to connect to the backend and display classification results in the demo
