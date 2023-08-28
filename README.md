# Fake_News_Detection

Project Overview: Genuine vs. Fake News Classification using Passive Aggressive Classifier

Step 1: Dataset Compilation and Integration
This project focuses on the classification of news articles into two categories: genuine and fake. To accomplish this, we begin by sourcing and compiling datasets containing both genuine and fake news articles. Subsequently, these datasets are merged to create a comprehensive dataset for analysis.

Step 2: Text Preprocessing
Effective text preprocessing is critical for ensuring accurate classification results. The preprocessing pipeline consists of the following key stages:

1.Tokenization: Tokenization involves breaking down each news article into individual words or tokens. This aids in the subsequent analysis by converting the textual information into a structured format.

2.Stemming: Stemming aims to reduce words to their base or root form. This process helps to standardize words and minimize variations. For instance, variations like "running," "runs," and "ran" would be stemmed to "run."

3.Stopword Removal: Stopwords, common words with minimal informational value (e.g., "and," "the," "is"), are eliminated from the text. This streamlines the dataset by focusing on words that convey more meaning.

Step 3: Text Vectorization
Text vectorization is the transformation of processed text into numerical representations, making it suitable for machine learning algorithms. We leverage established techniques such as TF-IDF (Term Frequency-Inverse Document Frequency) .
Step 4: Classification using Passive Aggressive Classifier
The heart of this project lies in the classification task, where we employ the Passive Aggressive Classifier. This classifier is particularly adept at binary classification tasks, such as our genuine vs. fake news categorization. It operates in an online learning manner, adapting its model incrementally as new data points are introduced.
