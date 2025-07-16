# 📊 Sentiment Analysis on Student Discussions About ChatGPT

## Overview

This notebook analyzes the sentiment of Reddit comments made by students discussing **ChatGPT** and its use in academic settings. These comments are filtered from a larger Reddit dataset to focus specifically on themes like:

- Homework help
- Exam preparation
- Assignments and writing
- Prompt engineering
- Ethical concerns (e.g., cheating)

Using **VADER Sentiment Analysis**, we classify each comment as:
- 🔵 Positive
- ⚪ Neutral
- 🔴 Negative

---

## 🗂️ Dataset

The dataset used here is:
[How Students Use ChatGPT – Filtered Reddit Dataset](https://www.kaggle.com/datasets/faizankhandeshmukh/how-students-use-chatgpt-filtered-reddit-dataset)

It contains thousands of Reddit comments filtered with keywords such as:
`chatgpt`, `homework`, `exam`, `university`, `prompt`, `cheating`, etc.

Each row includes:
- `body`: the actual comment
- `subreddit`: where it was posted
- `score`: upvotes
- `created_utc`: timestamp

---

## ⚙️ Methods Used

- **Text Preprocessing**
- **VADER Sentiment Scoring** via `nltk.sentiment.vader`
- **Sentiment Classification** (Positive, Neutral, Negative)
- **Data Visualization** using `matplotlib` and `seaborn`

We also extract top positive and negative examples and examine sentiment trends across subreddits.

---

## 📈 Key Visuals

- Bar chart of sentiment distribution  
- Top 5 positive and negative comments  
- Subreddit-wise sentiment breakdown *(optional)*

These help reveal how students **perceive**, **use**, and sometimes **question** ChatGPT in their studies.

---

## 💡 Insights

- Most students express **positive** views, appreciating ChatGPT’s utility.
- **Negative** sentiments often revolve around **cheating concerns** or lack of trust.
- Some comments show advanced **prompt engineering**, highlighting new student behavior patterns.

---

## Tools & Libraries

- Python  
- Pandas  
- NLTK (VADER)  
- Seaborn / Matplotlib  
- Jupyter / Kaggle Notebooks

---

## 🚀 How to Use

1. Clone the notebook or run it in Kaggle.
2. Analyze your own filtered Reddit data.
3. Extend the project to include:
   - Topic modeling
   - Emotion detection
   - Ethics-focused classification

---

## 📬 Feedback & Contributions

If you found this helpful or would like to collaborate on extending this to a full **ChatGPT-in-education research series**, feel free to fork or connect!

---

## 📎 Related Tags

`#chatgpt` `#sentiment-analysis` `#students` `#nlp` `#education` `#reddit` `#language-models` `#ethics-in-ai`
