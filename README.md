# Analysis of Individual Vote Choice in Recent U.S. Presidential Elections

Talia Fabregas | University of Toronto, Department of Statistical Sciences | Summer 2025

## Overview 👩‍🏫
This repository contains the code and data associated with my paper titled "Logistic Regression Analysis of Individual-Level Vote Choice in Recent U.S. Presidential Elections." 

## Abstract 📌
This project examines individual-level vote choice recent American presidential elections, employing frequentist, machine learning, and Bayesian logistic regression methods. Model selection via likelihood ratio testing indicates that interactions between race and key demographic factors (gender, education, region, and the urban-rural divide), along with approval of then-incumbent President Joe Biden and perceptions of economic conditions significantly improve logistic model fit on the 2024 Cooperative Election Study (CES) dataset. An L2-regularized logistic regression model trained and optimized via minibatch gradient descent on the 2024 CES dataset achieved 92.8\% accuracy on unseen test data. To further assess generalizability, the same model was re-trained on the 2020 Cooperative Election Study (CES) and 2016 Cooperative Congressional Election Study (CCES) datasets using analogous predictors and the same hyperparameters, and achieved 96.52\%  and 93.53\% accuracy, respectively, on unseen test data. Findings suggest that the interaction effects of race with demographic and geographic factors, as well as economy-related perceptions and approval of the incumbent president, significantly influenced vote choice in recent U.S. presidential elections and that a voter-level logistic modeling approach that incorporates micro- and macro-level predictors is a step towards an aggregate election forecast.

## Data 📊
* 2024 Cooperative Election Study (CES) Common Content dataset: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/X11EP6
* 2020 Cooperative Election Study (CES) Common Content dataset: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi%3A10.7910/DVN/E9N6PH
* 2016 Coopreative Congressional Election Study (CCES) dataset: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/GDF6Z0
  
## Contents 🗂️
* `00-Midterm-Version` contains my midterm paper, which this project builds upon
* `01-Midterm-Extension` contains the code used to preprocess the raw 2020 CES dataset and apply the model built and trained in my midterm paper to it.
* `code` contains the Python code that I wrote to preprocess the raw 2016 CCES dataset, apply a model analogous to the one built and trained in my midterm paper to it, and evaluate performance.
* `data` contains subsetted, cleaned versions of the 2024, 2020, and 2016 CES datasets that I used for analysis purposes.
* `sketches` contains model and dataset sketches for reference.

 ## Inspirations 🧠
This project was inspired by the works of Kuriwaki et al., Algara et al., and Camatarri. Their publications can be found using the following links:
* https://www.cambridge.org/core/journals/american-political-science-review/article/geography-of-racially-polarized-voting-calibrating-surveys-at-the-district-level/6BEF8C3000B763699C27A4F9E8590516
* https://www.cambridge.org/core/journals/ps-political-science-and-politics/article/forecasting-partisan-collective-accountability-during-the-2024-us-presidential-and-congressional-elections/9D6C577734D4FDB6CEED4256C60EE4BD
* https://www.cambridge.org/core/journals/ps-political-science-and-politics/article/predicting-popularvote-shares-in-us-presidential-elections-a-modelbased-strategy-relying-on-anes-data/CC6B59BAC456CAC43C96F27FBAAF2290#article

## Links 🔗
* Presentation slides: https://drive.google.com/file/d/16PgaKSNSkSFVpjWbx3uTo8kvK9p-QBTG/view?usp=sharing
* Presentation recording: https://drive.google.com/file/d/1MvFsuTPp22uJ7Li90uTQEXgxzQWUUVL6/view?usp=sharing
  
## LLM Usage 🤖
Chat GPT 3.5 and 5.0 were used for latex formatting, IEEE citations, code debugging, and grammar checks. 

## Acknowledgements 
I want to thank the following individuals:
* My supervisor, Professor Rohan Alexander at the University of Toronto, Department of Statistical Sciences
* Susan Hopkirk at the University of Toronto New College Writing Center for her assistance with my written work in this project.
