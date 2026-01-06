# 📘 Regression Analysis & Classification Project

**Author:** Allison Evanich

------------------------------------------------------------------------

## Project Overview

This project explores a real-world dataset using both **regression** and
**classification** techniques to better understand which factors may
influence the outcome of interest.

Rather than aiming to build a perfect predictive model, the primary goal
of this analysis was to practice and demonstrate a complete data science
workflow, including:

-   Data cleaning and preparation
-   Thoughtful feature selection
-   Model building and evaluation
-   Interpreting results honestly, including limitations

This project reflects an applied learning experience focused on
**process, reasoning, and transparency**.

------------------------------------------------------------------------

## Problem Statement

The objective of this project was to examine whether the available
features in the dataset could meaningfully explain or predict the target
outcome. Specifically, I wanted to understand:

-   Which variables appear most related to the outcome
-   Whether a statistical or machine-learning model could capture useful
    signal
-   What the results reveal about the **strength and limits** of the
    data

------------------------------------------------------------------------

## Project Workflow

### 1. Data Understanding

I began by reviewing the structure of the dataset to understand:
- What each column represented
- Which variables could reasonably be used as predictors
- Whether any data quality issues were immediately apparent

This step helped shape later decisions about which features to keep and
which to remove.

------------------------------------------------------------------------

### 2. Data Cleaning & Preparation

To prepare the data for modeling, I:
- Checked for missing values and inconsistencies
- Removed identifiers and fields that would not contribute to
prediction
- Applied transformations (such as log scaling) where appropriate to
improve model assumptions

These steps were taken to ensure the models reflected meaningful
patterns rather than noise or formatting issues.

------------------------------------------------------------------------

### 3. Feature Selection

Instead of using every available column, I focused on features that:
- Had a logical connection to the outcome
- Were available at prediction time
- Did not introduce data leakage

This helped keep the models simpler and easier to interpret.

------------------------------------------------------------------------

### 4. Modeling Approach

Two primary approaches were explored:

-   **OLS Regression** to better understand relationships between
    variables
-   **Random Forest Classification** to evaluate whether the outcome
    could be predicted using a non-linear model

These methods were chosen not for complexity, but for their ability to
support **interpretation and learning**.

------------------------------------------------------------------------

### 5. Model Evaluation

Model performance was assessed using:
- Accuracy, precision, recall, and F1-score for classification
- Coefficient interpretation and goodness-of-fit for regression

The Random Forest model achieved performance slightly above random
chance, with metrics around **0.56**, suggesting that while some signal
exists, the available features alone are not strong predictors of the
outcome.

Rather than viewing this as a failure, this result provided an important
insight:
The outcome is likely influenced by additional factors not captured
in the dataset, highlighting the limits of modeling without richer
features or domain context.

------------------------------------------------------------------------

## Key Takeaways

From this project, I learned that:

-   Not every dataset supports strong prediction, even with advanced
    models
-   Careful interpretation is just as important as model selection
-   Transparent discussion of limitations strengthens the credibility of
    an analysis
-   Feature engineering and domain knowledge often matter more than
    algorithm choice

------------------------------------------------------------------------

## Practical Value of This Work

While the models in this project are not intended for direct deployment,
the analysis demonstrates an approach that could support:

-   Exploratory decision-making
-   Identifying areas where better data collection is needed
-   Establishing a baseline for future modeling efforts

Most importantly, this project reflects how data science often works in
practice:
Iterative, imperfect, and focused on learning as much as predicting.

------------------------------------------------------------------------

## Repository Contents

    Evanich_DSC630_Project_portfolio.ipynb   # Full analysis with explanations  
    README.md                               # Project summary and context  

------------------------------------------------------------------------

## Future Improvements

If this project were extended, the next steps would include:

-   Deeper feature engineering
-   Incorporating additional domain-specific variables
-   Testing alternative models
-   Adding visualizations to better communicate results

------------------------------------------------------------------------

If you have questions about this project or would like to discuss the
analysis, feel free to reach out --- I'm always happy to talk through
the work and what I learned from it.
