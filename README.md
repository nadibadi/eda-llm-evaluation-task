# EDA Task for LLM Evaluation

This project contains a synthetic dataset and exploratory data analysis (EDA) task designed to evaluate the performance of large language models (LLMs).

## Contents
- Jupyter notebook with:
  - dataset generation
  - injected data quality issues
  - probabilistic target generation
  - validation and sanity checks

## Task design

The dataset includes realistic data issues:
- missing values
- inconsistent categories
- outliers
- invalid values
- duplicated records

The goal is to test whether a model can:
- detect data quality issues
- perform robust EDA
- derive meaningful insights under noise

## Target generation

The target variable is generated probabilistically using a logistic model:
- linear score → sigmoid → stochastic sampling

This ensures:
- signal is present but not trivial
- relationships are noisy and require reasoning

## Purpose

This project demonstrates the ability to:
- design structured EDA tasks
- generate synthetic datasets
- evaluate model behaviour on imperfect data
