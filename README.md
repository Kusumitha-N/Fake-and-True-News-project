# Fake and True News Detection

This project uses Machine Learning to automatically classify news articles as either "Real" or "Fake". 

## Project Overview
The goal of this project is to combat misinformation by building a predictive model that analyzes text patterns in news articles. 

## Technical Stack
- **Language:** Python
- **Environment:** Jupyter Notebook (Anaconda)
- **Libraries:** Pandas, Scikit-Learn
- **Algorithm:** Logistic Regression

## How it works
1. **Data Preprocessing:** The model cleans the text data and removes noise.
2. **Feature Extraction:** It converts text into numerical format using `TfidfVectorizer`.
3. **Model Training:** A `LogisticRegression` model is trained on a labeled dataset of news articles.
4. **Prediction:** The model achieves a high accuracy of approximately **98.5%** in distinguishing between real and fake news.

## How to use
- Load the dataset into the notebook.
- Run the `predict_news(text)` function to test any news headline!

