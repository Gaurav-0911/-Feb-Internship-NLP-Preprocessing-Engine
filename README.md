# 📊 NLP Preprocessing Engine

## 🚀 Project Overview

This project implements a **robust NLP preprocessing pipeline** designed to clean and transform raw, noisy text into structured and meaningful tokens. It simulates real-world text preprocessing required for machine learning and NLP applications.

---

## 🎯 Objectives

* Build a scalable and reusable preprocessing function
* Handle noisy real-world data (emojis, URLs, numbers, repeated characters)
* Perform token-level analysis and frequency analysis
* Develop a complete NLP pipeline with error handling

---

## 🛠️ Features

### 🔹 Text Preprocessing

* Convert text to lowercase
* Remove URLs and email patterns
* Remove numbers
* Remove special characters and emojis
* Handle repeated characters (e.g., "soooo" → "so")
* Remove extra spaces
* Tokenization (split text into words)
* Remove short tokens (≤2), except "no" and "not"

---

### 🔹 Stress Testing

* Tested on diverse real-world sentences
* Includes emojis, numbers, slang, URLs, and mixed case

---

### 🔹 Token Analytics

* Total number of tokens
* Number of unique tokens
* Average token length

---

### 🔹 Frequency Analysis

* Top 10 most frequent words
* Top 5 least frequent words

---

### 🔹 Full Pipeline

* Processes multiple sentences at once
* Returns:

  * Combined tokens
  * Cleaned sentences

---

### 🔹 Error Handling

Handles edge cases such as:

* Empty string
* Only emojis
* Only numbers

---

## 🧠 Technologies Used

* Python
* Regular Expressions (re)
* Collections (Counter)

---

## 📂 Project Structure

```
├── main.ipynb        # Jupyter Notebook (final solution)
├── README.md         # Project documentation
```

---

## ▶️ How to Run

1. Clone the repository:

```
git clone https://github.com/your-username/your-repo-name
```

2. Open the notebook:

```
cd your-repo-name
jupyter notebook
```

3. Run all cells to see the output.

---

## 📌 Example Output

* Cleaned tokens from noisy text
* Token statistics
* Word frequency analysis

---

## 🏁 Conclusion

This project demonstrates how to build a **production-ready NLP preprocessing pipeline** capable of handling real-world noisy data efficiently.

---

## 🙌 Acknowledgment

This project was completed as part of a **Data Science Internship Assignment**, focusing on practical NLP skills and real-world problem-solving.

---
