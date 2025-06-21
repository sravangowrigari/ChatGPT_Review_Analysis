# 📊 ChatGPT User Review Analysis

This project analyzes real-world user reviews of ChatGPT to uncover insights into what users love, what frustrates them, and how the experience can be improved. By performing sentiment analysis, issue detection, and time-series trend evaluation, we aim to contribute data-driven suggestions for enhancing ChatGPT’s user experience.

---

## 🔍 Project Objectives

- **Sentiment Analysis**  
  Classify reviews into Positive, Negative, or Neutral categories using NLP techniques.

- **Issue Identification**  
  Analyze negative reviews to detect frequently mentioned problems or complaints.

- **Time-Series Analysis**  
  Visualize how user sentiment has evolved over time to identify trends or shifts.

---

## 🛠 Technologies Used

- **Python**  
- **Pandas** – for data wrangling  
- **TextBlob** – for sentiment classification  
- **Matplotlib / Seaborn** – for data visualization  
- **WordCloud** – for issue identification in textual data  
- **Google Colab** – for interactive coding environment

---

## 📁 Dataset

- The dataset consists of:
  - `Review`: The text of the user’s review
  - `Ratings`: Star rating from 1 to 5
  - `Review Date`: Timestamp of the review

> 📎 Sample dataset file: `chatgpt_reviews.csv`

---

## 🚀 How to Run

1. Open the project in **Google Colab**
2. Upload the `chatgpt_reviews.csv` file
3. Copy and paste the code from `chatgpt_review_analysis.ipynb` or `main.py`
4. Run all cells to see:
   - Sentiment distribution
   - Word cloud for negative feedback
   - Monthly sentiment trend over time

---

## 📈 Sample Outputs

- 📊 **Bar chart** showing distribution of sentiment labels  
- ☁️ **Word cloud** highlighting top issues in negative reviews  
- 📆 **Line graph** displaying sentiment trend across months

---

## ✅ Key Insights

- Majority of users provide positive feedback, emphasizing ChatGPT’s helpfulness and intelligence.
- Negative reviews often mention issues like hallucinations, login problems, or slow responses.
- Notable sentiment changes align with product updates or public announcements.

---

## 🤝 Contributing

If you’d like to contribute to this project, feel free to fork the repo, improve the code, or apply advanced NLP models like VADER or BERT!

---

## 🙌 Acknowledgements

Thanks to the open-source NLP community and the users who provide candid feedback to help improve ChatGPT.

