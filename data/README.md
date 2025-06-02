## 📄 Data Card: 60k Stack Overflow Questions with Quality Rate

### 📌 Overview

This dataset contains 45,000 Stack Overflow questions collected between **December 31, 2015** and **February 29, 2020**. Each entry includes a question title, body, tags, and a quality label (`Y`) indicating one of **three distinct categories**. It's designed for analyzing question quality and supporting machine learning tasks like classification and NLP.

---

### 📊 Features

| Column Name    | Description                                              |
| -------------- | -------------------------------------------------------- |
| `Id`           | Unique question ID                                       |
| `Title`        | Question title text                                      |
| `Body`         | Full question body in HTML format                        |
| `Tags`         | Up to 5 tags per question (e.g., `<python>`, `<java>`)   |
| `CreationDate` | Date and time the question was posted                    |
| `Y`            | Label/category of the question quality (3 unique values) |

---

### 📈 Statistics

* **Tags**: Most frequent are `<python>` and `<java>` (each \~2%)
* **Title & Body**: All unique entries
* **Label Distribution (`Y`)**: Balanced across three categories (details not specified)
* **CreationDate Range**: From late 2015 to early 2020
* **Data Quality**: No missing or mismatched values reported

---

### 💡 Use Cases

* Question quality classification
* Training NLP models for Q\&A moderation
* Content recommendation and filtering
* Feature extraction from HTML-rich text

---

### 🔗 Link

[🔗 View dataset on Kaggle](https://www.kaggle.com/datasets/imoore/60k-stack-overflow-questions-with-quality-rate)