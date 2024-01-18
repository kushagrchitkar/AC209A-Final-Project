# Taste for Future Coffee World Domination

## Background and Motivation

Undoubtedly, coffee consumption is prevalent among adults, particularly for the unemployed graduate student dealing with sleep deprivation. For our collaborative team of five motivated Master’s students, coffee serves not only as a source of caffeine but also as a sensory delight for our taste buds. With aspirations of starting our own coffee chain in the foreseeable future, we recognize that the key to a good cup of coffee lies not only in the beans but also in understanding the various features that contribute to its quality. Our goal is to gain a thorough understanding of coffee beans and identify the best predictors of quality. Additionally, we aim to create our own test dataset using coffee found around Harvard and the SEC, analyzing and ranking them.

## Data

We have chosen the [Coffee Quality dataset](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi) for our project. This dataset includes information on different types of coffee, including details on origin, taste, ratings, and more. Our focus will be on studying the factors that make a coffee exceptional, utilizing taste variables such as aroma, balance, acidity, and those linked to the coffee's origin. Pre-processing will be essential, considering the presence of categorical variables and missing values.

## Scope

Our project will center around assessing coffee quality according to expert coffee tasters at CQI (Coffee Quality Institute). Given the subjective nature of this response, we are keen on identifying specific features that significantly contribute to the taster’s assessment of coffee quality. For model interpretability, we plan to apply multiple linear regression, emphasizing feature selection to address the high dimensionality of the data. As a robustness check, we may include Propensity Matching Score. Other methods in our toolkit include random forest regression, principal component analysis, and potentially a neural network to explore aspects of features that simpler models might overlook.

## Potential Issue

To ensure robustness, we may compare the similarity between metrics such as Q-score and Sweet Maria’s. There could be differences in these metrics, as highlighted in this [article](https://towardsdatascience.com/specialty-coffee-comparing-grading-methods-36777cae220f). This comparison will serve as a robustness check in our analysis.

## Workflow and Documentation

Our detailed workflow and all thought processes are thoroughly documented in the final notebook. For a comprehensive understanding of our methodology, findings, and analysis, please refer to the provided notebook.


