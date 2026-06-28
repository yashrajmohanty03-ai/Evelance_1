# 📱 Google Play Store App Analysis Dashboard

> An interactive data analytics dashboard built using Python and Plotly to analyze Google Play Store applications based on ratings, installs, reviews, category trends, and user sentiment.

---

# 📑 Table of Contents

- <a href="#project-title">Project Title</a>
- <a href="#brief-summary">Brief One Line Summary</a>
- <a href="#overview">Overview</a>
- <a href="#problem-statement">Problem Statement</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-and-technologies">Tools and Technologies</a>
- <a href="#methods">Methods</a>
- <a href="#key-insights">Key Insights</a>
- <a href="#dashboard-model-output">Dashboard / Visualizations</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#how-to-run-this-project">How to Run this Project?</a>
- <a href="#results-conclusion">Results & Conclusion</a>
- <a href="#future-work">Future Work</a>
- <a href="#author-contact">Author & Contact</a>

---

<h2 id="project-title">📌 Project Title</h2>

# Google Play Store App Analysis Dashboard

---

<h2 id="brief-summary">📝 Brief One Line Summary</h2>

An interactive data analytics project that explores Google Play Store applications using sentiment analysis, category filtering, and dynamic visualizations built with Plotly.

---

<h2 id="overview">📖 Overview</h2>

The Google Play Store hosts millions of applications across various categories. Understanding app performance based on ratings, reviews, installs, and user feedback can help developers and businesses make data-driven decisions.

This project analyzes Google Play Store app data along with user review sentiment data to uncover trends, identify high-performing applications, and visualize relationships between app size, ratings, installs, and user sentiment.

Interactive dashboards are developed using Plotly for enhanced data exploration and visualization.

---

<h2 id="problem-statement">⚠️ Problem Statement</h2>

With thousands of applications competing in the Play Store, identifying successful apps and understanding user behavior becomes challenging.

This project aims to:

- Analyze application performance metrics
- Study relationships between ratings and installs
- Evaluate user sentiment and subjectivity
- Filter high-performing applications
- Visualize key app market trends
- Generate actionable business insights

---

<h2 id="dataset">📂 Dataset</h2>

This project utilizes two publicly available datasets:

### 1. Google Play Store Dataset

Contains:

- App Name
- Category
- Rating
- Reviews
- Size
- Installs
- Type
- Price

### 2. User Reviews Dataset

Contains:

- App Name
- User Reviews
- Sentiment
- Sentiment Polarity
- Sentiment Subjectivity

### Dataset Files

```bash
googleplaystore.csv

googleplaystore_user_reviews.csv
```

---

<h2 id="tools-and-technologies">🛠️ Tools and Technologies</h2>

## Programming Language

- Python

## Libraries Used

- Pandas
- NumPy
- Plotly
- PyTZ
- Datetime

## Development Environment

- Jupyter Notebook
- VS Code

---

<h2 id="methods">⚙️ Methods</h2>

## Data Cleaning

Performed cleaning on:

- Ratings column
- Reviews column
- Installs column
- App Size column

## Data Transformation

- Converted ratings into numeric values
- Removed special characters from installs
- Converted app sizes into MB
- Handled missing values

## Sentiment Analysis Processing

- Processed Sentiment Subjectivity scores
- Aggregated review statistics per application
- Merged app data with review sentiment data

## Business Rule Filtering

Applications were filtered based on:

- Rating > 3.5
- Reviews > 500
- Installs > 50,000
- Subjectivity > 0.5
- Selected app categories

## Category Translation

Category names were translated into multiple languages for dashboard presentation.

## Visualization

Created interactive Plotly visualizations for:

- App Size vs Rating
- Installs Distribution
- Category Analysis
- Sentiment Insights

---

<h2 id="key-insights">📊 Key Insights</h2>

- Applications with higher ratings generally attract more installs.
- User sentiment plays a significant role in app popularity.
- Gaming and Entertainment categories dominate user engagement.
- Larger app size does not necessarily result in higher ratings.
- Highly reviewed applications tend to maintain better visibility in the marketplace.

---

<h2 id="dashboard-model-output">📈 Dashboard / Visualizations</h2>

## Dashboard Workflow

```text
Raw Dataset
      ↓
Data Cleaning
      ↓
Data Transformation
      ↓
Sentiment Aggregation
      ↓
Filtering Rules
      ↓
Interactive Plotly Dashboard
```

---

## Visualizations Included

### Bubble Chart

Displays:

- X-Axis → App Size (MB)
- Y-Axis → Rating
- Bubble Size → Installs
- Bubble Color → App Category

### Sentiment Analysis

- User Subjectivity Trends
- Review-Based App Insights

### Category Analysis

- Category Distribution
- High Performing Categories

---

<h2 id="project-structure">📁 Project Structure</h2>

```bash
Google_Play_Store_Analysis/

│
├── app_analysis.ipynb
├── googleplaystore.csv
├── googleplaystore_user_reviews.csv
├── README.md
└── visualizations/
```

---

<h2 id="how-to-run-this-project">🚀 How to Run this Project?</h2>

## Clone Repository

```bash
git clone https://github.com/yashrajmohanty03-ai/google-play-store-analysis.git

cd google-play-store-analysis
```

## Install Dependencies

```bash
pip install pandas numpy plotly pytz
```

## Launch Notebook

```bash
jupyter notebook app_analysis.ipynb
```

## Run All Cells

Execute all notebook cells sequentially to:

- Load datasets
- Clean data
- Perform sentiment aggregation
- Generate visualizations
- Display dashboard outputs

---

<h2 id="results-conclusion">📈 Results & Conclusion</h2>

## Results

Successfully:

- Cleaned and transformed raw app data
- Merged app and review datasets
- Applied business intelligence filters
- Generated interactive Plotly visualizations
- Identified high-performing applications
- Extracted sentiment-based insights

## Output
![image alt](https://github.com/yashrajmohanty03-ai/Evelance_1/blob/9b65f19eb7d890aab496a22d1c49ca3b1a5b4efc/ev1.jpeg)

## Conclusion

This project demonstrates how data analytics and visualization techniques can be used to uncover valuable insights from app marketplace data. By combining application metrics with user sentiment information, developers and businesses can better understand factors influencing app success.

---

<h2 id="future-work">🔮 Future Work</h2>

Future enhancements include:

- Streamlit dashboard deployment
- Power BI integration
- Predictive analytics for app success
- Advanced NLP-based review analysis
- Real-time Play Store monitoring
- Recommendation system for app categories

---

<h2 id="author-contact">👨‍💻 Author & Contact</h2>

## Yashraj Mohanty

### Areas of Interest

- Data Analytics
- Data Visualization
- Machine Learning
- Business Intelligence

### Contact

- GitHub: https://github.com/yashrajmohanty03-ai
- LinkedIn: https:// linkedin.com/in/yashraj-mohanty
- Email: yashrajmohanty3@gmail.com

---

<p align="center">
⭐ If you found this project useful, consider giving it a star on GitHub!
</p>
