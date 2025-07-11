# BBC-text-categorizer-Text-Classification-

📌 Project Summary:
This project focuses on building an AI-powered text classification model that can automatically categorize full BBC news articles into topics such as business, entertainment, politics, sport, and tech. The goal is to transform unstructured text data into structured insights using Natural Language Processing (NLP) and Deep Learning.

🔍 Problem Statement:
Given a news article's text, can we automatically predict which category it belongs to?

Manual categorization is time-consuming and error-prone. Automating this process improves efficiency in content management, journalism, and news aggregation systems.

⚙️ Technologies Used:
Python
TensorFlow / Keras (for deep learning)
Scikit-learn (for label encoding, metrics)
Dash by Plotly (for interactive web interface)
Kaggle BBC News Dataset (as training data)


📂 Workflow Breakdown:
1. Data Preprocessing:
- Cleaned the text (lowercasing, removing symbols)

- Tokenized and padded sequences to fixed length

- Encoded the categories into numeric labels

2. Model Building:
- Used an Embedding Layer to convert words into dense vectors

- Applied GlobalAveragePooling1D to flatten sequences

- Used Dense layers for classification

- Trained on ~2000 news articles with 5 categories

3. Evaluation:
- Achieved ~99.3% training accuracy and ~94.8% validation accuracy

- Evaluated using confusion matrix and classification report

4. Deployment:
- Built a Dash web app for users to input a full article and get real-time category predictions

- Prepared the project for deployment on Render.com
