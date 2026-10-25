# 📊 Consumer Buying Behavior Analysis — Smartphone Market

> An end-to-end consumer analytics project combining Google Looker Studio dashboards with Python machine learning to decode how people choose, buy, and live with their smartphones.

[![Looker Studio](https://img.shields.io/badge/Looker%20Studio-Dashboards-4285F4?logo=google&logoColor=white)](https://lookerstudio.google.com/)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Google Colab](https://img.shields.io/badge/Google-Colab-F9AB00?logo=googlecolab&logoColor=white)](https://colab.research.google.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](#-license)

---

## 🧭 Live Dashboards

Explore the interactive dashboards hosted on GitHub Pages:

👉 [View the Live Dashboard Navigator](https://sarathyb.github.io/Consumer-Buying-Behaviour-Analytics/)

| # | Dashboard | Focus Area |
|---|-----------|------------|
| 1 | Amazon Dashboard | Purchase behaviour, deals, trust & convenience |
| 2 | Flipkart Dashboard | Platform comparison & buying patterns |
| 3 | Consumer Research & Decision Drivers | Pre-purchase research & feature priorities |
| 4 | Demographic | Age, income, and education segmentation |

---

## 📌 Abstract

This project explores the key factors that shape how consumers make decisions when purchasing smartphones. Using primary survey data, it combines the storytelling power of Data Visualization dashboards with the analytical depth of Machine Learning and Business Intelligence to uncover patterns in buyer behaviour.

The findings reveal that consumers are highly practical — focusing more on specifications and price than on social influence. E-commerce platforms like Amazon and Flipkart attract buyers with deals, trust, and convenience, while long-term satisfaction is driven primarily by phone performance and battery life.

Through this study, we aim to help smartphone brands and retailers understand what truly matters to consumers — both before and after purchase.

---

## 🎯 Problem Statement

In today's crowded smartphone market, every brand fights for consumer attention. Yet many fail to understand what drives people to choose one device or platform over another.

This project addresses that challenge by exploring questions such as:

- What features do buyers value most?
- How do income, age, and education shape preferences?
- Which e-commerce platforms do consumers trust, and why?
- What issues influence long-term satisfaction?

By answering these, we hope to bridge the gap between what brands think customers want and what customers actually experience.

---

## 🧩 Scope

The project covers the entire consumer decision journey — from research to purchase and post-purchase satisfaction. Specifically, it includes:

- Demographic profiling of respondents
- Analysis of pre-purchase research habits and decision factors
- Comparison of experiences across Amazon, Flipkart, and brand websites
- Sentiment analysis of customer feedback using machine learning

---

## 💡 Motivation

Smartphone buyers are more informed than ever, yet brands often rely on guesswork rather than data. The motivation behind this project was to turn raw survey responses into meaningful insights — showing how customer expectations, satisfaction, and loyalty evolve over time.

By blending BI dashboards with machine learning, we aimed to build a complete picture of the modern smartphone consumer: data-driven, rational, and expressive.

---

## 🏗️ Architecture

```text
┌──────────────────┐
│  Google Form     │  ← Survey: Consumer Buying Behavior Analysis
│  (Data Capture)  │
└────────┬─────────┘
         │ responses
         ▼
┌──────────────────┐
│  Google Sheets   │  ← Raw data storage
└────────┬─────────┘
         │
         ├─────────────────────┐
         ▼                     ▼
┌─────────────────┐    ┌────────────────────┐
│ Looker Studio   │    │ Python (Colab)     │
│ 4 Dashboards    │    │ • Cleaning         │
│ • Amazon        │    │ • EDA              │
│ • Flipkart      │    │ • Sentiment Model  │
│ • Research      │    │   (NLTK)           │
│ • Demographic   │    └──────────┬─────────┘
└────────┬────────┘               │
         │                        │
         └────────────┬───────────┘
                      ▼
         ┌────────────────────────┐
         │  GitHub Pages Website  │
         │  (Dashboard Navigator) │
         └────────────────────────┘
```

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Survey & Data Collection | Google Forms, Google Sheets |
| Business Intelligence | Google Looker Studio |
| Data Analysis | Python — Pandas, NumPy |
| Visualization | Seaborn, Matplotlib |
| Machine Learning / NLP | NLTK, Scikit-learn |
| Notebook Environment | Google Colab |
| Hosting | GitHub Pages |

---

## 🚀 Methodology

### 1. Data Sources
The data was collected through a Google Form survey titled Consumer Buying Behavior Analysis. It covered:

- Demographics
- Buying preferences
- Satisfaction with platforms
- Open-ended feedback

Responses were automatically recorded in Google Sheets for processing and analysis.

📋 [Take the Survey](https://docs.google.com/forms/d/e/1FAIpQLScOqUJzz9FEh2zLdTTlH1Wivx-8aP3hSoN8NQvGz23MMNocKw/viewform) — just takes 5 minutes!

### 2. Step-by-Step Workflow

| Step | Description |
|------|-------------|
| ① Data Collection | Survey distributed across age and income groups |
| ② Data Cleaning | Removed incomplete/inconsistent entries; standardized categorical responses |
| ③ Dashboard Creation | Designed 4 interactive dashboards for demographics, purchase behavior & satisfaction |
| ④ Exploratory Data Analysis (EDA) | Python used to study relationships between income, brand preference & satisfaction |
| ⑤ Machine Learning | Text feedback classified into positive / neutral / negative sentiment using NLTK |

---

## 📓 Notebooks

The full Python analysis is available as Colab notebooks:

| # | Notebook | Description |
|---|----------|-------------|
| 1 | [Notebook 1](https://gist.github.com/SARATHYB/236f0ff75315bcfada9febf54e60c0c5) | Data cleaning & preprocessing |
| 2 | [Notebook 2](https://gist.github.com/SARATHYB/0bea0fe822675346da2f3e9f89414499) | Exploratory Data Analysis (EDA) |
| 3 | [Notebook 3](https://gist.github.com/SARATHYB/b7a40e6e0b60e7973223a7c22e78b35e) | Sentiment analysis model |

> Notebooks are rendered live on the GitHub Pages site under the 📓 Notebooks tab.

---

## 🔍 Key Insights

- Practical buyers — specifications and price dominate over social influence
- Platform trust — Amazon and Flipkart win on deals, trust, and convenience
- Long-term satisfaction — driven by performance and battery life
- Social influence — surprisingly low impact on final purchase decisions

---

## 🤝 Contribute to the Data

Help make this analysis richer! If you've bought a smartphone recently, your input matters.

### Would you like to Contribute to the data? (Just takes 5 mins)

👉 [Fill the Survey](https://docs.google.com/forms/d/e/1FAIpQLScOqUJzz9FEh2zLdTTlH1Wivx-8aP3hSoN8NQvGz23MMNocKw/viewform?usp=sharing)

Your responses help improve the dashboards and sentiment model. Every submission counts! 🙏

---

## 📂 Project Structure

```text
consumer-buying-behavior/
│
├── index.html              # Dashboard navigator (hosted on GitHub Pages)
├── README.md               # This file
├── notebooks/              # Python analysis (mirrored from Gists)
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   └── 03_sentiment_analysis.ipynb
├── data/
│   └── survey_responses.csv    # Anonymized survey data
└── docs/
    └── abstract.md             # Full project report
```

> If the folders above are not present yet, you can remove them or create them later.

---

## 🖥️ Running Locally

To preview the dashboard navigator on your machine:

```bash
git clone https://github.com/SARATHYB/Consumer-Buying-Behaviour-Analytics.git
cd Consumer-Buying-Behaviour-Analytics
python -m http.server 8000
```

Then open http://localhost:8000 in your browser.

> A local server is needed because Looker Studio and Gist embeds will not render correctly from file:// URLs.

---

## 🌐 Deploying to GitHub Pages

1. Push `index.html` to the repository's `main` branch
2. Go to Settings → Pages
3. Under Build and deployment, select Deploy from a branch
4. Choose `main` and folder `/ (root)`, then Save
5. Your site will be live at `https://<username>.github.io/<repo-name>/`

---

## 📜 License

This project is licensed under the MIT License — feel free to use, modify, and share with attribution.

---

## 🙏 Acknowledgements

- Google Looker Studio — for the powerful free BI platform
- Google Colab — for the free notebook environment
- NLTK — for the sentiment analysis toolkit
- All survey respondents — for making this analysis possible

---

## 📬 Contact

**Sarathy B**  
GitHub: [@SARATHYB](https://github.com/SARATHYB)

---

<p align="center">
  <i>Built with 📊 data, ☕ coffee, and a lot of curiosity.</i>
</p>
