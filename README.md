# Internship-Project

# Beginner ML: Classification & Regression Projects

This repository contains two fundamental machine learning projects designed for beginners to explore core concepts in **Classification** and **Regression** using Python and Scikit-learn.

## Projects Included

| Project | Concept | Algorithm | Libraries Used |
| :--- | :--- | :--- | :--- |
| **Spam Email Classifier** | Classification | Naive Bayes (`MultinomialNB`) | `scikit-learn` |
| **Stock Price Predictor** | Regression | Linear Regression | `yfinance`, `scikit-learn`, `pandas` |



##  1. Spam Email Classifier (Classification)

This project trains a model to distinguish between legitimate emails (**Ham**) and unwanted emails (**Spam**).

### Key Learning Outcomes

* Understanding **Classification** problems.
* **Text Vectorization** using `CountVectorizer` to convert text data into numerical features.
* Applying the **Naive Bayes** algorithm, which is highly effective for text data.

### How to Run

1.  Open the file `spam_classifier.py` (or the relevant Jupyter Notebook cell).
2.  Run the script. It uses a small, internal dummy dataset to demonstrate the prediction process.

---

## 📈 2. Stock Price Predictor (Regression)

This project demonstrates how to use historical data to predict a continuous numerical value (the closing stock price).

### Key Learning Outcomes

* Understanding **Regression** problems.
* Working with **time-series data** and fetching real data using the `yfinance` library.
* The limitations of using a simple **Linear Regression** model for volatile financial data. 

[Image of Linear Regression plot with data points]


### How to Run

1.  **Install dependencies** (if running locally):
    ```bash
    pip install yfinance pandas scikit-learn matplotlib
    ```
2.  Open the file `stock_predictor.py` (or the relevant Jupyter Notebook cells).
3.  The model fetches the last 2 years of **AAPL (Apple)** stock data by default.

---

## Setup and Installation

### Recommended Environment

The best way to run and experiment with these files is using **Google Colab** (a free cloud-based Jupyter environment) to avoid local installation issues.

### Local Setup (Optional)

If you prefer to run locally, ensure you have Python installed, then install the required libraries:

```bash
# Install core libraries
pip install scikit-learn numpy pandas matplotlib

# Install the library for real stock data
pip install yfinance
