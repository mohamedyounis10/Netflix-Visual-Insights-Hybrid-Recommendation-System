# Netflix Movies and TV Shows 🍿🎥✮⋆˙ — EDA 📊 & Hybrid Recommendation System 🤖

This repository contains a comprehensive data analysis and a hybrid recommendation engine for **Netflix** content using a dataset from Kaggle:
- 📒 A **Jupyter Notebook** for data cleaning, Exploratory Data Analysis (EDA), and NLP-based feature engineering.
- 🤖 A **Hybrid Recommendation System** that suggests content based on genres, directors, and release years.

> 💡 **Note**: The project focuses on creating a "Netflix-like" experience by calculating similarity scores between titles to provide highly relevant suggestions.

---

## Table of Contents 🧭

- [Project Structure](#project-structure-)
- [Overview](#overview-)
- [Dataset](#dataset-)
- [Notebook](#notebook-)
  - [Steps](#steps-)
  - [Models](#models-)
  - [Results](#results-)
- [Power BI Dashboard](#power-bi-dashboard-)
- [Getting Started](#getting-started-)
  - [Requirements](#requirements-)
  - [Run the Notebook](#run-the-notebook-)
- [HTML Header Template](#html-header-template-)
- [Author](#author-)
- [Acknowledgments](#acknowledgments-)
- [License](#license-)

---

## Project Structure 🗂️

```text
Netflix/
├─ Dataset/
│  └─ netflix_titles.csv
├─ Dashboard/
|  └─ Dataset/
|     └─ clean_data.csv
|  └─ Images/
|     └─ img1 
|     └─ img2
│  └─ Netflix.pbix
├─ docs/
│  └─ header.html
└─ notebook.ipynb
```

---

## Overview ✨
The goal of this project is to:
- 🔎 Understand Netflix Trends: Analyze the growth of content over the years and identify dominant genres.
- 🧩 Text Processing: Use Natural Language Processing (NLP) to convert movie descriptions and metadata into numerical vectors.
- 📊 Data Visualization: Visualize the distribution of Movies vs. TV Shows and the top-producing countries.
- 🧪 Build a Recommender: Develop a hybrid algorithm using TF-IDF and Cosine Similarity.
- 📊 Building a simple BI dashboard (Power BI)

---

## Dataset 📦

Location: `Dataset/netflix_titles.csv`

Key columns used:
- 🎥 Type: Movie or TV Show.
- 🎭 Listed_in: Genre classifications.
- 🎬 Director & Cast: The creative team behind the content.
- 📅 Release Year: The year the title was originally released.
- 🔞 Rating: Content age ratings (e.g., TV-MA, PG-13).
- 📝 Description: A brief summary of the title.

---

## Notebook 📒

File: `notebook.ipynb`

### 1. Data Preprocessing 🛠️
- Cleaning: Handling missing values in director and cast by labeling them as "Unknown".
- Date Conversion: Converting date_added into a standard datetime format.
- Feature Engineering: Creating a "Metadata Soup" that combines key features (Genres, Director, Description) for the recommendation engine.

### 2. EDA Insights 📈
- Content Explosion: A significant surge in content additions was observed between 2016 and 2019.
- Genre Dominance: International Movies and Dramas are the most frequent categories.
- Production Hubs: The United States and India lead in content production.

### 3. Recommendation Logic 🤖
The hybrid system utilizes:
- TF-IDF Vectorization: To analyze text patterns in descriptions and genres.
- Cosine Similarity: To calculate the distance between titles in a multi-dimensional space.
- Weighted Ranking: Prioritizing titles that share the same director or are from a similar era.

---

## Power BI Dashboard 📈

Folder: `Dashboard/`

- `Netflix.pbix`: Power BI report

Open the `.pbix` file using **Power BI Desktop**.

What you can do with the dashboard:
- 📌 Explore key distributions 
- 💳 Review billing/insurance breakdowns
- 🔎 Slice & filter visuals for quick insights
  

---

## Getting Started 🚀

### Requirements 🧰

To run the notebook, you’ll typically need:
- Python 3.x
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

### Run the Notebook ▶️

1. Open `notebook.ipynb` in Jupyter / VS Code.
2. Run cells top-to-bottom.

---

## HTML Header Template 🧩

File: `docs/header.html`

- A simple, reusable **HTML header** (brand + navigation) with clean CSS.
- You can use it in a static website or GitHub Pages.

---

## Author ✍️

- Name: **Mohamed Younis**

---

## Acknowledgments 🙏

- **Internship 🏢**: [Uneeq Interns](https://www.linkedin.com/company/uneeq-interns/)

---

## License 📄

Add a license that matches how you want others to use your work (e.g., MIT).
If you tell me your preference, I can add the `LICENSE` file too.




