## Table of Contents
- [Code and dataset](https://github.com/tissyamalik/mcc-airline-sentiment-analysis#code-and-dataset)
- [Bugs and Feature Requests](https://github.com/tissyamalik/mcc-airline-sentiment-analysis#bugs-and-feature-requests)
- [Submitting a pull request](https://github.com/tissyamalik/mcc-airline-sentiment-analysis#submitting-a-pull-request)
- [Copyright](https://github.com/tissyamalik/mcc-airline-sentiment-analysis#copyright)

## Code and dataset
The [python code](https://github.com/tissyamalik/mcc-airline-sentiment-analysis/blob/main/airline-classification.py) and the [data file](https://github.com/tissyamalik/mcc-airline-sentiment-analysis/blob/main/airline.csv) is on github.

# mcc-airline-sentiment-analysis
3-class sentiment airline ratings classification on twitter dataset 

**Problem Statement**: To book the best airline which is economically convenient as well as provides great hospitality. We all spend so much time searching for the best airline which is cheap, ensures least delays in flights , provides traveller friendly deals and reliable service.

**Dataset**: The data was extracted from kaggle. Twitter data was scraped from February of 2015 and classify to— positive, negative, and neutral tweets. The dataset contains information about tweets of 6 major U.S airlines: Virgin America, Delta, Southwest, American, US Airways and United.
Link to the dataset is https://www.kaggle.com/crowdflower/twitter-airline-sentiment.

**Challenges** : No homogenity in data 

**Outcome**: Linear Discriminant Analysis (LDA) outperformes Decision Tree (DT) and Random Forest (RF) machine learning model with macro-average F1 score = 0.68

**Insights**
1 US Airways have a least positive sentiment followed by American and United.
2.Virgin America has most balanced sentiments
3. Customer Service Issue is the main negative reason for US Airways,United,American,Southwest,Virgin America
4. Late Flight is the main negative reason for Delta.
5. Virgin America has the least count of negative reasons (all less than 60)
6. Contrastingly to Virgin America, airlines like US Airways,United,American have more than 500 negative reasons (Late flight, Customer Service Issue)

## Bugs and Feature requests
Identified a bug in the code or a feature requests, [please open a new issue](https://github.com/tissyamalik/mcc-airline-sentiment-analysis/issues/new/choose)

## Submitting a pull request
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://kcd.im/pull-request)

## Copyright
Code and documentation copyright 2020–2026 [the Author](https://github.com/tissyamalik/mcc-airline-sentiment-analysis/graphs/contributors). Code released under the MIT License. Docs released under [Creative Commons](https://creativecommons.org/licenses/by/3.0/).

