## 📄 Data Card: 60k Stack Overflow Questions with Quality Rate

### 📌 Overview

This dataset contains **45,000 questions** sampled from a larger corpus of **60,000 Stack Overflow posts** collected between **December 31, 2015** and **February 29, 2020**. Each question includes a title, body (in HTML), tags, and a categorical label `Y` that indicates one of three quality types:

* `HQ`: High-quality posts with no edits.
* `LQ_EDIT`: Low-quality posts with negative scores and multiple community edits, but still open.
* `LQ_CLOSE`: Low-quality posts closed by the community with no edits.

It's suitable for tasks involving text classification, moderation, and content quality analysis.

---

### 📊 Features

| Column Name    | Description                                         |
| -------------- | --------------------------------------------------- |
| `Id`           | Unique identifier of the question                   |
| `Title`        | Title of the question                               |
| `Body`         | HTML-formatted body of the post                     |
| `Tags`         | Up to 5 programming-related tags                    |
| `CreationDate` | Date and time the post was created                  |
| `Y`            | Quality label (one of: `HQ`, `LQ_EDIT`, `LQ_CLOSE`) |

---

### 📈 Summary Stats

* **Most common tags**: `<python>`, `<java>` (each \~2%)
* **No missing values**: All fields are complete and validated
* **Creation date range**: From late 2015 to early 2020
* **Label balance**: 3 categories with relatively even distribution

---

### 💡 Use Cases

* Supervised learning for quality prediction
* Text and HTML parsing tasks
* Community moderation modeling
* Tag relevance and recommendation experiments

---

### 🔗 Source

[🔗 View dataset on Kaggle](https://www.kaggle.com/datasets/imoore/60k-stack-overflow-questions-with-quality-rate)