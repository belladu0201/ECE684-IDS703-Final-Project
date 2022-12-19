# ECE684-IDS703-Final-Project
## NLP Final Project FA22: Predicting Personality Type with Social Media Posts: A Machine Learning Approach to MBTI Classification
<img src="https://i.redd.it/eogag5y764z71.png" width="600" height="400">

# Team Members
There are three people in the group: Xiaoyu Chen, Beibei Du, Xianchi Zhang.

# Motivation
We are interested in the well-known personality test: MBTI, which stands for Myers–Briggs Type Indicator. Although there are some bias toward this personality test, we want to use Natural Language Processing knowledge to see if the prediction is significant. 

# Introduction
There are in total of 16 personalities based on the MBTI.
[Describe the MBTI test from research paper by the end of 11/23].

# Research Question
1. Is it possible to predict a user's MBTI type based on their posts?
2. Do the extroverted people have less posts tha introverted people? (Optional)

# Data
We decided to use the data from Kaggle: [MBTI Dataset](https://www.kaggle.com/datasets/datasnaek/mbti-type).

In this dataset, we have 8675 observations and 2 columns. The two columns are `type` and `posts`.
# Tools
We will use the language of Python for this project. The relevant tools include: Git, Github, EDA(matplotlib, seaborn, altair, pandas), NLP(TBD), Report(Overleaf(latex), Google slides).

# Approaches (Algorithms)

1. We can use language modeling to predict the category of personality based on the words that distingusih the most from the other categories.
2. Since we are required to have 2 generative models and 2 discriminative models, we consider the following models:
- Generative:Generative Adversarial Networks (GANs), Hidden Markov Models (HMMs)
- Discriminative: SVMs, Logistic Regression, Neural Networks, etc

# Results
- Naive Bayes: 21%
- SVM: 66%
- MLP: 65%
- Bert: 60+%

# Discussion
Through our four algorithms: Naive Bayes, SVM, MLP, and Bert, three of them (except Naive Bayes) have been strong methods to predict the personality types based on the text data: posts. However, there is still room for improvement in the performance of these models or potential more powerful models, and further research and development is necessary to expand the potential applications. Ultimately, this project showcases the power of utilizing machine learning algorithms (both discriminative and generative models) to delve deeper into the complexities of personality traits (MBTI or beyond it) and their connections to online posts and other formats of speech.

# Reference
[ChatBoxes & MBTI](https://chatbotslife.com/write-a-post-and-i-will-tell-you-who-you-are-5e0e1b74aa8b)

[MBTI dataset](https://www.kaggle.com/datasets/datasnaek/mbti-type)

[NLP MBTI SAMPLE Deployment 1](https://github.com/samrat-halder/personality-detection-with-BERT-RoBERT)

[NLP MBTI SAMPLE Deployment 2](https://github.com/janitbidhan/MBTI)

[NLP MBTI SAMPLE Deployment 3](https://github.com/Pranshu-Bahadur/nlp-mbti)
