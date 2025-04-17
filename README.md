# Unsupervised-Learning---Customer-Review-Project
# Customer_Reviews

## Unsupervised Machine Learning on Customer Reviews

This project focuses on analyzing and uncovering hidden patterns in **customer reviews** using **unsupervised machine learning techniques**. It includes natural language processing (NLP), clustering, sentiment analysis, and a fully deployed web app to explore and visualize insights from textual feedback. The model is deployed as **Customer_Reviews**.

---

## Project Overview

- **Objective**: Extract meaningful insights from customer feedback using clustering and sentiment analysis.
- **Approach**: Clean and preprocess review text, apply K-Means clustering to group similar reviews, and use VADER and TextBlob for sentiment evaluation.
- **Deployment**: The project is deployed via **Streamlit**, providing an interactive dashboard to explore results.

---

## Dataset

The dataset consists of customer reviews with a focus on:
- **Review Text** (raw input)
- **Cleaned Review Text** (processed for NLP)
- **Cluster Assignments**
- **Sentiment Labels** (Positive, Negative, Neutral)

>  *The dataset is either user-provided or synthetic for demonstration purposes.*

---

## Technologies Used

- **Python**
- **NLTK** – Tokenization, Stopwords, Lemmatization
- **TextBlob** – Sentiment Analysis
- **VADER** – Lexicon-based Sentiment Scoring
- **scikit-learn** – TF-IDF Vectorization, K-Means Clustering, Silhouette Score
- **WordCloud** – Visual representation of review themes
- **Pandas & NumPy** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Streamlit** – App deployment and user interface

---

## Data Preprocessing Steps

1. **Text Cleaning** – Remove punctuation, digits, and lowercase the text.
2. **Stopword Removal** – Filter out common words using NLTK’s English stopword list.
3. **Lemmatization** – Reduce words to their base form for normalization.
4. **TF-IDF Vectorization** – Transform cleaned text into numerical feature vectors.

---

## Unsupervised Learning (Clustering)

- Applied **K-Means** to cluster customer reviews based on their textual similarity.
- Used **Silhouette Score** to determine optimal number of clusters.
- Cluster labels help identify different customer opinion themes (e.g., service quality, pricing concerns, product satisfaction).

---

## Sentiment Analysis

- Used **VADER** for compound sentiment scoring and classification.
- Integrated **TextBlob** for polarity and subjectivity scoring (optional).
- Reviews are classified into:
  - **Positive**
  - **Neutral**
  - **Negative**

---

## WordCloud Visualization

- Word clouds are generated for each sentiment class, providing an intuitive understanding of the most frequent terms associated with customer opinions.

---

## How to Use

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Customer_Reviews.git
   cd Customer_Reviews
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Streamlit app**
   ```bash
   streamlit run streamlit_reviews.py
   ```

---

## Live App

You can interact with the deployed app here:  
[Customer Reviews Streamlit App](http://localhost:8501/)

---

## Future Improvements

- Integrate **topic modeling** (e.g., LDA) for deeper theme extraction.
- Enable **live review submissions** and real-time feedback analysis.
- Add **multi-language support** for global datasets.
- Store insights in a **database** and create time-series trend dashboards.

---

## Conclusion

This project demonstrates how unsupervised learning and sentiment analysis can be used to extract insights from customer feedback. With an interactive dashboard, businesses and analysts can explore hidden patterns in textual data and make data-driven decisions.

---

## Contact

For collaboration, questions, or feedback:

- **GitHub**: [@Ife926](https://github.com/Ife926)
- **LinkedIn**: [Ifechukwu okonkwo](http://www.linkedin.com/in/ifechukwu-okonkwo-9073a0252)
- **Deployed App**: [Customer_Reviews](http://localhost:8501/)
