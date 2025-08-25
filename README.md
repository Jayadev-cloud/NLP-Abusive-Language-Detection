🚨 NLP – Abusive Language Detection

This project focuses on detecting abusive/offensive language using Natural Language Processing (NLP) techniques and Machine Learning models. The system is designed to classify whether a given word or text is offensive or not offensive.

🔑 Key Features

Preprocessing:

Text cleaning and normalization

Tokenization

POS (Part-of-Speech) tagging – displaying first 20 tokens with POS tags

Named Entity Recognition (NER):

Extracted 5 sample NER tags

Complete dataset NER tag markup

NER tag distribution visualizations

Word Embeddings:

Created embeddings for words

Visualized embeddings in vector space

Model Training & Evaluation:
Implemented and compared multiple models for classification:

Model	Accuracy
Logistic Regression	0.8991
Multinomial Naive Bayes	0.8533
Support Vector Machine (SVM)	0.9030
DistilBERT	0.8679

DistilBERT Integration:

Generated sentence embeddings

Encoded text for deep learning analysis

Provided real-time label prediction with confidence

🎯 Example Prediction

Input: Enter text for DistilBERT label prediction
Output:

Predicted Label: OFFENSIVE

Prediction Confidence: 100.00%

📊 Insights

SVM achieved the highest accuracy (90.3%), making it the best-performing traditional ML model.

Logistic Regression also performed competitively with 89.9% accuracy.

DistilBERT, though slightly less accurate, provides contextual understanding and high-confidence predictions.

⚙️ Tech Stack

Languages: Python

Libraries & Tools: Scikit-learn, SpaCy, NLTK, Transformers (HuggingFace), Matplotlib/Seaborn

Models: Logistic Regression, Multinomial Naive Bayes, SVM, DistilBERT

📌 Applications

Detecting abusive/offensive words on social media platforms

<img width="855" height="351" alt="image" src="https://github.com/user-attachments/assets/e507befc-ac47-48c8-933b-4c9f3e588e5a" />
<img width="443" height="196" alt="image" src="https://github.com/user-attachments/assets/ec3994d9-52e2-4519-96f7-8de069341cb4" />




Monitoring toxic comments in online communities

Supporting content moderation systems
