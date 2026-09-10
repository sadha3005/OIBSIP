# Sentiment Analysis using NLP and Machine Learning

## Project Overview

In this project, sentiment analysis was performed on Twitter text data using **Natural Language Processing (NLP)** and machine learning techniques.

The main goal of the project is to classify text data based on sentiment and identify whether the given text expresses a positive, negative, or neutral opinion.

The text data was cleaned and transformed into numerical features using **TF-IDF (Term Frequency-Inverse Document Frequency)**. Two machine learning models, **Naive Bayes** and **Logistic Regression**, were trained and evaluated.

---

## Objective

The main objectives of this project are:

- Analyze Twitter text data.
- Perform text preprocessing using NLP techniques.
- Convert text into numerical features using TF-IDF.
- Train machine learning classification models.
- Compare the performance of different models.
- Select the best-performing model based on evaluation results.
- Provide real-world business applications of sentiment analysis.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Text Preprocessing

The Twitter text data was cleaned using the following preprocessing techniques:

1. Lowercase conversion
2. Punctuation removal
3. Tokenization
4. Stopword removal

After preprocessing, **TF-IDF Vectorization** was used to convert the text data into numerical features suitable for machine learning models.

---

## Machine Learning Models

Two classification models were trained and evaluated:

- Naive Bayes
- Logistic Regression

### Model Performance

| Model | Accuracy |
|---|---:|
| Naive Bayes | 71.64% |
| Logistic Regression | 75.95% |

---

## Model Comparison

**Logistic Regression** performed better than Naive Bayes, achieving an accuracy of approximately **75.95%**.

Therefore, Logistic Regression was selected as the **best-performing model** among the two tested models for this dataset.

---

## Real-World Applications

Sentiment analysis can be applied in various business and organizational scenarios:

### Customer Feedback Analysis

Companies can analyze customer reviews and social media comments to understand customer opinions.

### Negative Feedback Detection

Businesses can identify negative feedback and take corrective action to improve their products and services.

### Brand and Product Monitoring

Organizations can monitor public opinion about their products, services, or brands.

### Customer Satisfaction

Sentiment analysis can help businesses track customer satisfaction and support better decision-making.

---

## Final Recommendation

Logistic Regression is the preferred model among the two tested models because it achieved higher accuracy and more balanced precision, recall, and F1-score compared with Naive Bayes.

Future improvements could include:

- Better text cleaning
- Handling noisy Twitter data
- Stemming or lemmatization
- Experimenting with advanced NLP models
- Improving model performance through feature engineering

---

## Conclusion

This project demonstrates how Natural Language Processing and machine learning can be used to analyze sentiment in Twitter text data.

The comparison of two machine learning models showed that **Logistic Regression achieved the highest accuracy of 75.95%**, outperforming Naive Bayes with 71.64% accuracy.

Sentiment analysis can provide valuable insights into customer opinions, public feedback, and brand perception, helping organizations make better data-driven decisions.

---

## Project Files

- `README.md` – Project documentation
- `Sentiment_Analysis.ipynb` – Jupyter Notebook containing the complete analysis
- Charts/visualizations – Outputs generated during the analysis

### Dataset Note

The original dataset is not included in this repository if its file size exceeds GitHub's upload limit. The analysis was performed using the original dataset locally.

---

## Skills Demonstrated

- Natural Language Processing
- Text Preprocessing
- TF-IDF Vectorization
- Machine Learning
- Classification
- Model Evaluation
- Data Visualization
- Sentiment Analysis
- Business Insights

- **Author: Sadha A**
