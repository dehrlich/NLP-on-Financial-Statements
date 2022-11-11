# NLP on Financial Statements

### Project Motivation:

1. To perform Natural Language Processing (NLP) on 10-k financial statements to generate an alpha factor.

### The notebook is separated into two parts:
1. The first part covers data collection and inspection, text cleaning and pre-processing.
2. The second part covers sentiment analysis of 10-k financial statements using 'Loughran McDonald Sentiment Word Lists,' assessing the Jaccard and cosine similarity between subsequent 10-ks, implementing the cosine similarity as an alpha factor, and assessing the factor returns performance.

### File Descriptions:


    project_5.ipynb
    | - Jupyter notebook containing all data collection, cleaning and preprocessing, sentiment word list construction, text similarity exploration, cosine similarity alpha factor construction, alpha factor return calculation and evaluation, and turnover cost calculation.
    helper.py
    |- helper file to abstract some data collection and import statements
    project_helper.py
    |- helper file to abstract graphing functions
    project_test.py
    |- unit tests to flag any major errors
    README.md


### Installations:
- This project uses the 'Alphalens' library to complete performance analysis of alpha factors. Alphalens was created by Quantopian, a crowd-sourced investment fund, which closed in 2020. See [alphalens github page](https://github.com/quantopian/alphalens) for specifics.
- You will need a python environment with the following:
    - see the `requirements.txt` file for specific packages and versions
    - python verson 3.6 or higher

### Instructions:
1. Run each cell in 'project_5.ipynb' in sequence. Make sure the Jupyter notebook is in the same level of the directory as 'helper.py', 'project_helper.py', 'project_tests.py', and 'tests.py'.