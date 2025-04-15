# News-recommendation-system-using-MIND-Microsoft-News-Recommendation-Dataset

# 🧠 Reinforcement Learning News Recommender

This project applies reinforcement learning techniques to news recommendation. Using user behavior and article metadata, it leverages contextual multi-armed bandit algorithms to personalize what news gets shown.

---

## 🚀 Try it Now on Google Colab

Click the button below to open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1cdI2FViRTQ4lhswR-GEnf3rdDu1lJPrd?usp=sharing)

---

## 📂 Dataset

The following datasets are automatically downloaded when the notebook runs:

- `behaviors.tsv`: User impression and click logs
- `news.tsv`: News content, titles, categories, and metadata

✅ You do not need to upload any files manually — the notebook will handle everything using `gdown`.

---

## 🧰 Environment Setup

All dependencies are installed automatically in the first cell of the notebook:

- `pandas`
- `numpy`
- `scikit-learn`
- `mabwiser`
- `sentence-transformers`
- `gdown`

For local usage, install dependencies using:

```bash
pip install pandas numpy scikit-learn mabwiser sentence-transformers gdown
