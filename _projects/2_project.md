---
layout: page
title: ICU Mortality Prediction Model
description: An ICU mortality prediction project comparing multiple ML approaches on real patient data.
img: /assets/img/med3.png
importance: 2
category: work
giscus_comments: false
---

# ICU Mortality Prediction Model

This project focused on predicting ICU patient mortality from a Kaggle healthcare dataset. I used Python, Pandas, and PyTorch to clean the data, compare multiple model families, and iterate toward the strongest-performing approach.

## Highlights

- Built a full training pipeline for preprocessing, feature comparison, evaluation, and hyperparameter tuning
- Tested multiple architectures including logistic regression, random forest, and neural networks
- Chose the best-performing model based on precision and recall tradeoffs
- Reached approximately 99% accuracy during the final tuned runs

## What I learned

Working with medical data made model evaluation more important than headline accuracy. Comparing multiple approaches and understanding where they performed well helped turn this into more than just a training exercise.

## Predictive Model AUC Performance

<div class="row justify-content-center ">
    <div class="col-sm-8 mt-3  mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/AUC.png" title="AUC of XGBoost model" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">ROC curve from one of the evaluated models, used to compare class separation performance during experimentation.</div>
