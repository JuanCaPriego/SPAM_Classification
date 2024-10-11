# SPAM_Classification
## Description:
This code uses an SMS database with spam and not spam text to compare machine learning models for the classification of the texts. I used Sci-kit Learn for the quick application of various models and the easy comprehension of concepts for performance analysis so I could determine if the model tends to overfit. I had to look into some challenges regarding the model selection, which better served in the non-training and testing phase. As the dataset used for the project has an imbalance towards the not-spam class, many models with higher accuracy classified all the validation texts as not spam, proving overfitting and discarded models with higher scores.
The goal of this project was to learn how I can approach NLP tasks and understand basic concepts within the subject. For this purpose, test multiple models to classify SPAM SMS.
## Pre-requisites
To run this project, popular IDEs where it can run are:
- Google Colab
- Jupyter notebook
- VS Code with the Jupyter Notebook extension
One can find the libraries used for the project in the "requirements.txt" file and can be installed using the following command:
`pip install -r requirements.txt`
## Conclusions:
After training and analysis of some of the metrics for machine learning models. Many showed great performance in learning certain tendencies of the SMS texts, although when tested with non-tested data, many of the models showed to be biased towards the not spam class as it was the most populated class. In this final comparison with validation examples, the model that provided more accurate results for real classification was the **Complement Naive Bayes** model, which correclty classified the non-tested data of the validation segment.
