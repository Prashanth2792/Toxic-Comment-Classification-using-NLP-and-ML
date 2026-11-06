# 🛡️ Toxic Comment Classification Using NLP and Machine Learning

## 📌 Project Overview

The **Toxic Comment Classification** project uses Natural Language Processing (NLP) and Machine Learning techniques to identify toxic comments in text.

The system classifies user comments into two categories:

- **Toxic:** Comments containing harmful, offensive, or abusive language.
- **Not Toxic:** Comments that do not fall into the toxic category.

The project demonstrates a complete Machine Learning workflow, from data collection and text preprocessing to model training, evaluation, deployment, and monitoring.

## 🎯 Objectives

- Understand and analyze textual data.
- Perform text cleaning and preprocessing using NLP techniques.
- Convert text into numerical features using Bag of Words and TF-IDF.
- Build and compare multiple classification models.
- Perform hyperparameter tuning.
- Select the best-performing model.
- Save and load the trained model using Pickle.
- Deploy the model using Gradio.

## 📂 Dataset Information

**Dataset:** Toxicity English Dataset

**Source:** [Toxicity Dataset – GitHub](https://github.com/surge-ai/toxicity)

Dataset URL:
`https://raw.githubusercontent.com/surge-ai/toxicity/main/toxicity_en.csv`

**Dataset Details:**
- Total records: 1,000
- Total columns: 2
- Input column: `text`
- Target column: `is_toxic`
- Classification type: Binary Classification

**Target Distribution:**
- Toxic: 501
- Not Toxic: 499

## 🛠️ Technologies & Libraries

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| NLTK | Text preprocessing |
| Scikit-learn | Machine Learning |
| Pickle | Model saving and loading |
| Gradio | Web application deployment |
| Jupyter Notebook | Development environment |

## 🔄 Project Workflow

The project follows these 14 stages:

1. **Business Understanding:** Define the problem and project objectives.
2. **Data Collection:** Load the toxicity dataset.
3. **Data Understanding:** Perform EDA and analyze the dataset.
4. **Feature Engineering:** Separate input features and target labels.
5. **Train-Test Split:** Divide the dataset into training and testing sets.
6. **Text Preprocessing:** Clean text, remove stopwords, and perform lemmatization.
7. **Feature Extraction:** Convert text into numerical features using BoW and TF-IDF.
8. **Model Building:** Train three classification algorithms.
9. **Model Evaluation:** Evaluate models using classification metrics.
10. **Hyperparameter Tuning:** Optimize model parameters using GridSearchCV.
11. **Best Model Selection:** Select the model based on evaluation performance.
12. **Final Evaluation:** Evaluate the selected model on test data.
13. **Model Saving & Loading:** Save and reload the trained model using Pickle.
14. **Deployment:** Build a web interface using Gradio.

## 🤖 Machine Learning Algorithms

Three classification algorithms are implemented:

1. Logistic Regression
2. Decision Tree Classifier
3. Support Vector Machine (LinearSVC)

The models are compared using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

**Model Selection:** The best model is selected based on its cross-validation F1-score, with final performance checked on the test dataset.

## 🧹 NLP Techniques

The following text preprocessing techniques are used:

- Lowercase conversion
- HTML tag removal
- URL removal
- Special character removal
- Tokenization
- Stopword removal
- Lemmatization

**Feature Extraction:**
- Bag of Words (BoW)
- Term Frequency–Inverse Document Frequency (TF-IDF)

## 📊 Model Evaluation

The models are evaluated using standard classification metrics.

| Metric | Description |
|---|---|
| Accuracy | Overall correct predictions |
| Precision | How many predicted toxic comments are actually toxic |
| Recall | How many actual toxic comments are identified |
| F1-Score | Harmonic mean of precision and recall |

The final model performance is determined by the actual test results.

## 💾 Model Saving and Loading

Pickle is used to save and reuse:

- TF-IDF Vectorizer
- Best Trained Classification Model

Saved files:

- `tfidf_vectorizer.pkl`
- `best_toxicity_model.pkl`

This allows predictions without retraining the model every time.

## 🌐 Deployment Using Gradio

A simple interactive web application is developed using Gradio.

**Application Features:**
- User-friendly text input.
- Automatic text preprocessing.
- Real-time toxicity prediction.
- Displays Toxic or Not Toxic classification results.

Users can enter a comment and receive the model's prediction through the web interface.

## 🚀 Future Enhancements

- Use larger and more diverse toxicity datasets.
- Implement multi-label toxicity classification.
- Explore advanced NLP models such as BERT.
- Improve prediction accuracy through additional experiments.
- Develop a more advanced web interface.
- Introduce continuous model performance monitoring.

## 🎓 Learning Outcomes

Through this project, I gained practical experience in:

- Understanding NLP concepts.
- Text preprocessing and feature extraction.
- Building classification models.
- Comparing and evaluating ML algorithms.
- Hyperparameter tuning.
- Saving and loading ML models.
- Deploying ML applications using Gradio.
- Understanding basic model monitoring.


## 👨‍💻 Author

** Kota Prashanth Yadav**

B.Tech – Data Science | 2026 Graduate

Interested in Machine Learning, Natural Language Processing, Data Science, and Artificial Intelligence.

---

⭐ If you find this project interesting, feel free to explore the repository and share your feedback!
