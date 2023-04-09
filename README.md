# Recommender System for the IBM Watson Studio Platform

This repository contains a Recommender System which suggests new articles to the users of the IBM Watson Studio Platform.



1. Exploratory Data Analysis
2. Rank-based recommendations
3. User-user-based recommendations
4. Content-based recommendations
5. Matrix factorization


## Table of Contents

- [Recommender System for the IBM Watson Studio Platform](#recommender-system-for-the-ibm-watson-studio-platform)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [How to Use This Project](#how-to-use-this-project)
    - [Installing Dependencies for Custom Environments](#installing-dependencies-for-custom-environments)
  - [Notes on Theory](#notes-on-theory)
  - [Notes on the Implemented Analysis and Modeling](#notes-on-the-implemented-analysis-and-modeling)
    - [Summary of Contents](#summary-of-contents)
  - [Results and Conclusions](#results-and-conclusions)
  - [Next Steps, Improvements](#next-steps-improvements)
  - [References and Links](#references-and-links)
  - [Authorship](#authorship)


## Dataset

## How to Use This Project

The directory of the project consists of the following files:

```
.
├── Instructions.md
├── README.md
├── Recommendations_with_IBM.ipynb
├── article_recommender
│   └── __init__.py
├── conda.yaml
├── data
│   ├── articles_community.csv
│   ├── top_10.p
│   ├── top_20.p
│   ├── top_5.p
│   ├── user-item-interactions.csv
│   └── user_item_matrix.p
├── project_tests.py
├── requirements.txt
├── setup.py
├── starter/
└── tests
    ├── conftest.py
    └── test_article_recommender.py
```

You can run the notebook at leas in two ways:

1. In a custom environment, e.g., locally or on a container. To that end, you can create a [conda](https://docs.conda.io/en/latest/) environment and install the [dependencies](#installing-dependencies-for-custom-environments) as explained below.
2. In Google Colab. For that, simply click on the following link:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mxagar/airbnb_data_analysis/blob/master/00_AirBnB_DataAnalysis_Initial_Tests.ipynb)


### Installing Dependencies for Custom Environments

If you'd like to control where the notebook runs, you need to create a custom environment and install the required dependencies. A quick recipe which sets everything up with [conda](https://docs.conda.io/en/latest/) is the following:

```bash
# Create environment with YAML, incl. packages
conda env create -f conda.yaml
conda activate rec-ibm

# Or
conda create --name rec-ibm pip python=3.9
conda activate rec-ibm
# and install version-specific pip dependencies
pip install -r requirements.txt

# To track any changes and versions you have
conda env export > conda.yaml
pip list --format=freeze > requirements.txt
```

List of most important dependencies:

- A
- B

## Notes on Theory

## Notes on the Implemented Analysis and Modeling

### Summary of Contents

- [ ] A
- [ ] B

## Results and Conclusions

## Next Steps, Improvements

## References and Links

- A
- B
- C
- Link
- Link

## Authorship

Mikel Sagardia, 2023.  
No guarantees.

If you find this repository useful, you're free to use it, but please link back to the original source.
