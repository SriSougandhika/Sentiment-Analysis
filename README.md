# 🌟 Sentiment Analysis with Random Forest and SHAP Interpretability

This project performs **sentiment analysis** on social media text data using **Random Forest Classifier** after reducing the sentiment categories to just *Positive* and *Negative*. It includes interpretability with **SHAP**, misclassification analysis, and confusion matrix visualization.

## 📌 Dataset
The dataset is sourced from Kaggle:  
[Twitter Sentiment Dataset (Filtered for Positive/Negative)](https://www.kaggle.com/datasets/kaushiksuresh147/twitter-sentiment-analysis)

## 📊 Workflow Summary
1. Load and clean data
2. Filter sentiments with frequency ≥ 15
3. Reduce sentiment to *Positive* and *Negative*
4. Vectorize using **TF-IDF**
5. Train with **Random Forest**
6. Evaluate with accuracy, confusion matrix, and misclassified samples
7. Interpret model using **SHAP**

## 📈 Results
- **Accuracy**: ~83%
- Misclassified examples shown for inspection
- Confusion matrix plotted
- SHAP values visualized for class-wise feature importance

## 🧠 Model Interpretability
SHAP helps visualize which words pushed the model toward Positive or Negative sentiments.

## 🙌 Credits
Project by Sri – an aspiring Data Scientist exploring AI in creative ways!
