# MACHINE-LEARNING-MODEL-IMPLEMENTATION

company: CODTECH IT SOLUTIONS

NAME: DANDE SRIDHAR

INTERN ID : CT08DA47

DOMAIN: PYTHON

DURATION: 8 WEEKS

MENTOR: NEELA SANTHOSH

📝 Description: Spam Email Detection using Naive Bayes Classifier
In this task, a machine learning model was implemented to classify SMS messages as spam or ham (not spam) using scikit-learn.

📌 Objective:
To create a predictive classification model using scikit-learn that can automatically detect whether a given message is spam.

📂 Dataset:
The dataset used is a publicly available SMS Spam Collection Dataset containing 5,000+ labeled SMS messages, where each message is labeled as either:

ham (legitimate message) or

spam (unsolicited commercial message).

⚙️ Methodology:
Data Preprocessing:

Loaded dataset from a .tsv file.

Encoded labels (ham → 0, spam → 1).

Split data into training and testing sets.

Feature Extraction:

Used CountVectorizer to convert text messages into a matrix of token counts.

Model Building:

Implemented a Multinomial Naive Bayes classifier, well-suited for text classification tasks.

Model Evaluation:

Evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

📊 Results:
Accuracy: ~98.5%

High precision and recall for both spam and ham classes.

The model correctly identified the majority of spam and ham messages, with very few false positives or false negatives.

📌 Conclusion:
The Naive Bayes model performed exceptionally well for classifying SMS messages, making it a suitable and efficient choice for real-time spam detection applications.
