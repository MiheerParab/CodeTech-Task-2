# CodeTech-Task-2

Name -Miheer Devendra Parab

Company - CODTECH IT SOLUTIONS PVT.LTD

InternID -CT12ENH

Role -Artificial intelligence Intern

Span -December 17th, 2024 to February 17th, 2025.


📧 Text Classification and Spam Mail Detection


📝 Project Overview
This project focuses on building a text classification system to detect spam emails using the Bag-of-Words (BoW) model and Naive Bayes algorithm. The goal is to preprocess email data, extract meaningful features, and classify messages into "spam" or "not spam" categories with high accuracy.

📂 Dataset Information
Dataset Used: SpamAssassin Public Dataset
Description: The dataset consists of labeled email messages categorized as "spam" or "ham" (not spam).
Key Columns:
Email Text: Raw email content.
Label: Indicates whether the email is "spam" (1) or "ham" (0).
🔧 Workflow
1. Data Loading and Inspection
Load the dataset into a Pandas DataFrame.
Inspect data structure and perform exploratory data analysis (EDA).
2. Data Preprocessing
Clean text data:
Remove punctuation, special characters, and extra spaces.
Convert text to lowercase.
Remove stopwords using NLTK.
Apply stemming or lemmatization for normalization.
Handle missing values if any.
3. Feature Extraction
Use the Bag-of-Words (BoW) model to convert text data into numerical format.
Transform the text data into a sparse matrix using CountVectorizer from scikit-learn.
4. Model Training
Split the dataset into training and testing sets.
Train a Naive Bayes classifier:
MultinomialNB: Best suited for text data.
Evaluate the model on the test data.
5. Model Evaluation
Metrics used:
Accuracy
Precision, Recall, and F1-score
Confusion Matrix
🛠️ Technologies and Libraries
Programming Language: Python
Libraries:
Data Handling: Pandas, NumPy
Text Preprocessing: NLTK, re
Feature Extraction: scikit-learn
Model Building: Naive Bayes (MultinomialNB)
Visualization: Matplotlib, Seaborn
The model successfully detects spam emails with high performance, showcasing the effectiveness of BoW and Naive Bayes for text classification.

🚀 How to Run the Project
Prerequisites
Python 3.x installed on your system.
Required libraries installed (see requirements.txt).
Steps
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/spam-mail-detection.git
cd spam-mail-detection
Install dependencies:
bash
Copy code
pip install -r requirements.txt
Run the Jupyter Notebook:
bash
Copy code
jupyter notebook notebooks/spam_detection.ipynb
Or execute the standalone script:
bash
Copy code
python spam_detector.py
📜 Key Features
Text Cleaning: Removes noise for better model accuracy.
BoW Implementation: Converts text into numerical vectors.
Naive Bayes Classifier: Lightweight and effective for text data.
Model Metrics: Evaluates the system's performance comprehensively.
🤝 Contributing
Contributions are welcome! Please follow the steps below:

Fork this repository.

Create a new branch (git checkout -b feature-branch-name).

Commit your changes (git commit -m 'Add some feature').

Push to the branch (git push origin feature-branch-name).

Open a pull request.
