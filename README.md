# 📰 Text Summarization using Extractive and Abstractive Techniques

This project implements **text summarization** using both extractive and abstractive methods. It leverages `spaCy` for extractive summarization and a pretrained `BART` model for abstractive summarization. Additionally, it evaluates the summarization quality using ROUGE metrics.

---

## 📂 Dataset

The dataset used is in CSV format (`train.csv`, `test.csv`, `validation.csv`) and includes:
- `article`: Full news article text.
- `highlights`: Summary provided for the article.

> Note: Only the first 1000 rows from each CSV are used for demonstration purposes.

---

## 🧰 Setup & Installation

1. **Clone the repository**

```bash
git clone https://github.com/your-username/text-summarization.git
cd text-summarization
