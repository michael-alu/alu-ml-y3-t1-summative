# Predicting Late Delivery Risk in Global Supply Chains

ALU ML (Year 3, Trimester 1) Summative Project — Model Training and Evaluation.

## Problem

Late deliveries are one of the most common and costly failure points in supply
chains, eroding customer trust and creating downstream operational costs. This
project asks: **at the moment an order is placed, can we predict whether it is at
risk of arriving late** — using only information available at order time — so that
operations teams can intervene proactively (expedite, re-route, or notify the
customer)?

## Dataset

[DataCo Smart Supply Chain for Big Data Analysis](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis)
— 180,519 orders across five global markets (LATAM, Europe, Pacific Asia, USCA,
Africa), with order, customer, product, and shipping details. See
[`data/README.md`](data/README.md) for download details.

## Approach

The notebook in [`notebooks/`](notebooks/) builds an end-to-end pipeline that
compares **classical machine learning** (Scikit-learn: logistic regression,
decision trees, random forest, gradient boosting) against **deep learning**
(TensorFlow Sequential API, Functional API, and tf.data pipelines) for binary
classification of `Late_delivery_risk`.

## Repository Structure

```
├── data/         # dataset + download instructions
├── notebooks/    # main analysis notebook (all experiments)
├── results/      # experiment logs / saved figures
└── requirements.txt
```

## Links

- [Report](https://drive.google.com/file/d/1VLewb9aXnj2unDsy3abasS1JOZzmLJ3m/view?usp=sharing)
- [Demo video](https://www.canva.com/design/DAHNhF_qkFs/xclCYStJza8_HtrGyh2NWg/watch?utm_content=DAHNhF_qkFs&utm_campaign=designshare&utm_medium=link2&utm_source=uniquelinks&utlId=h4b3f8a6b37)
