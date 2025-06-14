# 🎮 Video Game Market Analysis

## 📌 Project Overview

This project explores the global video game market using data since 1980s of different consoles to identify trends and factors that influence a game's commercial success. I analyzed the impact of platform, genre, region, rating systems, and both critic and user scores. The main goal was to uncover actionable insights that publishers, developers, and marketers can use to better position their products in the market. It's a simulation of a real-world scenario from 2016, focusing on forecast future trends.

---

## 📓 Notebook Access

All analysis, visualizations, and hypothesis testing were developed in a Jupyter Notebook, using Python libraries such as `pandas`, `matplotlib`, `seaborn`, and `scipy`.

For a better viewing experience of the Jupyter Notebook, acess through NBViewer

---

## 📊 Dataset

The dataset is a simulation of public video game sales and review database. It includes:

- Game names, platforms, release years  
- Genre, publisher, and ESRB rating  
- Regional and global sales  
- Critic and user scores

---

## 🧹 Data Preprocessing

Key steps included:

- Standardizing column names
- Fixing inconsistent or missing data  
- Removing outliers and rare categories  
- Converting datatypes for numerical operations  
- Handling `tbd` values with proper NaN conversion  

These steps ensured the dataset was clean and analysis-ready.

---

## 🎯 Business Question

> What parameters influence the commercial success of a video game?

I limited the analysis to games released **after 2011**, focusing on newer games and platforms that represent the actual scenario and market trends, and explored how platform, region, genre, rating and critic/user scores affect games sales.

---

## 🌍 Regional Platform Trends

Globally, the most sucessful  platforms, by total sales, since 2012 were: 3DS, PS3, PS4, Xbox 360 and Xbox One. However, this may change with a regional focus.

| Region         | Top Platforms                             |
|----------------|--------------------------------------------|
| **North America** | Xbox 360, PS3, PS4, Xbox One, 3DS         |
| **Europe**        | PS3, PS4, Xbox 360, 3DS, **PC**           |
| **Japan**         | 3DS, PS3, **PSP**, **PSV**, PS4          |

- Japan favors local brands (Sony, Nintendo).  
- PC is stronger in Europe than other regions.  
- NA mirrors global trends due to large market share.

---

## 📈 User & Critic Scores

- Games with higher ratings tends to sell more.  
- Correlation between critic scores and sales: **~33%**  
- Many top-selling games had no critic reviews, showing that branding and genre can outweigh formal scores.

---

## 🔞 Age Ratings by Region

- Japan showed a strong skew toward E-rated (Everyone) games, a direct reflection of the dominance of the 3DS, known for child and family-friendly content.
- NA and EU favored **M-rated** (Mature) games, consistent with their top genres like Shooter and Action.

- **Business takeaway**: Regional age preferences   should inform content curation, particularly for localized game stores or digital marketing.

---

## 🎮 Genre Preferences

- **Globally popular**: Action, Shooter, Sports, RPG  
- **Japan**: Prefers Role-Playing, Platformers and Fighting

---

## 📊 Hypothesis Testing

Two key tests:

1. **User score comparison: Xbox One vs PC**  
   - No statistically significant difference in user scores.
   - Suggests that platform alone may not strongly influence perceived game quality.
     
2. **User score comparison: Action vs Sports games**  
   - **Statistically significant difference** found.
   - Indicates that **genre does impact user satisfaction**.

---

## 💼 Possible Applications

- Guide **regional marketing strategies** for publishers  
- Prioritize **genre-platform combinations** that yield higher satisfaction  
- Inform digital storefront curation based on age rating trends  
- Forecast sales likelihood based on early critic scores

---

## 🔧 Possible Improvements

- Use machine learning models to predict sales  
- Track long-term trends across more granular year ranges

---

## Final Conclusions

This video game market analysis provided comprehensive insights into key factors influencing game sucess across different platforms, genres, regions, and audience segments. This study reinforces that regional preferences, platform dynamics and content type are deeply connected, and critical to market sucess.

---

