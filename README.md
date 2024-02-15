# Activity_Recognition_system

### Time Series Classification Project Overview
This project comprises two integral parts aimed at effectively classifying human activities based on time series data obtained from a Wireless Sensor Network.

### Part 1: Feature Creation/Extraction
In this initial phase, the primary objective is to extract meaningful features from the time series data. Time series classification presents intriguing challenges within the realm of machine learning, particularly when applied to the classification of human activities. Extracted features serve as vital inputs for building classification models in subsequent parts.

### Part 2: Binary and Multiclass Classification
The second part extends the classification task into binary and multiclass scenarios, utilizing logistic regression as the primary classification technique. Although this section is not submitted with Homework 3, it builds upon the features extracted in the previous part. Participants are strongly encouraged to commence early due to the complexity of building various models. The tasks encompass:

#### Binary Classification Using Logistic Regression:
Initially, the focus is on distinguishing bending from other activities using logistic regression. Scatter plots of features extracted from specific time series instances aid in visualizing classification outcomes.

#### Binary Classification Using L1-penalized Logistic Regression:
Expanding on the previous task, L1-penalized logistic regression is employed for binary classification. Instead of using p-values for variable selection, L1 regularization offers an alternative approach to feature selection.

#### Multi-class Classification (The Realistic Case):
This section addresses the realistic scenario of multi-class classification, where activities are classified into multiple categories. The following tasks are undertaken:

Finding the Best l for L1-penalized Multinomial Regression: Similar to the approach used in Part 4(b)i, the optimal number of time series segments (l) is determined to build an L1-penalized multinomial regression model.
Multi-class Classification Using Naïve Bayes Classifier: Classification tasks are repeated using a Naïve Bayes classifier, exploring both Gaussian and Multinomial priors.

#### Comparative Analysis: 

A comparative analysis is conducted between the L1-penalized multinomial regression model and the Naïve Bayes classifier to identify the superior method for multi-class classification in the given problem context.
Through these comprehensive analyses, participants gain valuable insights into effective feature extraction, model building, and evaluation techniques in time series classification. Detailed instructions and guidance are provided to ensure a thorough understanding of the tasks involved.
