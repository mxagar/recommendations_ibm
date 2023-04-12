# Recommender System for the IBM Watson Studio Platform

This repository contains a Recommender System which suggests new articles to the users of the IBM Watson Studio Platform.

I took the starter code for this repository from a Udacity assignment project and modified it to the present form, which deviates significantly from the original form; see [`starter`](starter).

:construction: On-going work.

:warning: Even though the project is finished, I will finish the production code and this documentation `README.md` in the coming days.

Contents:

- [x] Exploratory Data Analysis
- [x] Rank-based recommendations
- [x] User-user-based recommendations
- [x] Content-based recommendations
- [x] Matrix factorization
- [ ] Package with production code
- [ ] Testing


## Table of Contents

- [Recommender System for the IBM Watson Studio Platform](#recommender-system-for-the-ibm-watson-studio-platform)
  - [Table of Contents](#table-of-contents)
  - [Dataset](#dataset)
  - [How to Use This Project](#how-to-use-this-project)
    - [Installing Dependencies for Custom Environments](#installing-dependencies-for-custom-environments)
  - [Notes on Theory](#notes-on-theory)
  - [Notes on the Implemented Analysis and Modeling](#notes-on-the-implemented-analysis-and-modeling)
  - [Results and Conclusions](#results-and-conclusions)
  - [Next Steps, Improvements](#next-steps-improvements)
  - [References and Links](#references-and-links)
  - [Authorship](#authorship)


## Dataset

:construction: TBD.

## How to Use This Project

:construction: TBD.

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

:construction: TBD.

## Notes on the Implemented Analysis and Modeling

:construction: TBD.

## Results and Conclusions

:construction: TBD.

- Accuracy is not the best metric here, because the user-item matrix contains almost only zeros.
- Explain A/B testing: how to separate user groups? which metrics tracked?

## Next Steps, Improvements

:construction: TBD.

## References and Links

:construction: TBD.

- [Netflix: System Architectures for Personalization and Recommendation - Earliest Architecture Design](https://netflixtechblog.com/system-architectures-for-personalization-and-recommendation-e081aa94b5d8)
- [Netflix: Articles Recommender Systems](https://netflixtechblog.com/tagged/recommendations)
- [Evaluating Recommender Systems: Choosing the best one for your business](https://medium.com/recombee-blog/evaluating-recommender-systems-choosing-the-best-one-for-your-business-c688ab781a35)
- [An introduction to SVD and its widely used applications](https://towardsdatascience.com/an-introduction-to-svd-and-its-widely-used-applications-f5b8f19cb6cb)
- [How Does the Funk Singular Value Decomposition Algorithm work in Recommendation Engines?](https://medium.datadriveninvestor.com/how-funk-singular-value-decomposition-algorithm-work-in-recommendation-engines-36f2fbf62cac)
- [Solving Cold User problem for Recommendation system using Multi-Armed Bandit](https://towardsdatascience.com/solving-cold-user-problem-for-recommendation-system-using-multi-armed-bandit-d36e42fe8d44)

## Authorship

Mikel Sagardia, 2023.  
No guarantees.

If you find this repository useful, you're free to use it, but please link back to the original source.
