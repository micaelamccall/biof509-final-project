# Final project for BIOF 509 Machine Learning in Python
### Can personality traits and demographics predict drug use? Using supervised learning to classify drug consuption behavior.

# Project Goals

Human behavior is delightfully complex. This complexity is reflected in this [drug consumption dataset](http://archive.ics.uci.edu/ml/datasets/Drug+consumption+%28quantified%29), which contains demographic info as well as scores from personality inventories. This dataset is interesting to me because constructs from personality inventories can often seem abstract, so it's informative to explore how they relate to a concrete behavior. This dataset includes scores from the NEO personality inventory (neuroticism, extraversion, openness to experience, agreeableness, and conscientiousness), the BIS-11 (impulsivity), and ImpSS (sensation seeking). Last, it includes info on whether each individual had used a number of drugs. 

In this project, I explored the ability of three supervised learning algorithms to predict whether an individual has used a specific drug. I explored and visualized parameter selection for each model, as well as how metrics can help us select the best model for a problem. 


# Setup

- My anaconda venv can be created by running  `conda env create -f environment.yml` in the terminal

# Usage

- `drug_consumption.ipynb` contains all the code for the project and comments

# Findings

Based on test-set accuracy (0.76) and ROC AUC (0.81), I found that the SVC model performed better than other models in predicting whether or not an individaul had used cannabis. 
