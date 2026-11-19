
# Video Game Sales Analysis

**Python-Based Data Analysis & Tableau Dashboard | Global Video Game Sales**

## Overview

This project analyzes global video game sales data to uncover patterns across **genre, platform, publisher, and region**. The analysis combines **data cleaning, exploratory data analysis, statistical testing, and interactive visualization** to generate actionable insights for game developers and publishers.

The goal is not only to understand historical sales trends but also to provide **data-driven recommendations** for future game development, platform selection, and regional market targeting.

## Executive Summary

The analysis reveals that the global video game market is highly concentrated, with a relatively small number of publishers dominating sales. **Genre preferences, platform selection, and regional differences** play important roles in shaping market performance.

**Action** leads global genre sales, while **Nintendo** stands out among leading publishers. Regional comparisons also reveal distinct platform preferences, suggesting that a **one-size-fits-all strategy is unlikely to be effective** across different markets.

These findings highlight the importance of combining historical sales performance with region-specific market insights to support more informed development, distribution, and investment decisions.

---

## Business Objectives

- Identify the best-performing video game genres, platforms, and publishers.
- Analyze historical trends in game releases and global sales.
- Compare platform performance and consumer preferences across regions.
- Investigate differences in sales performance across platforms.
- Translate analytical findings into actionable business recommendations.

---

## Dataset

The project uses the Video Game Sales dataset from Kaggle, containing historical sales records across multiple gaming platforms and geographic markets.

| Attribute | Description |
| --- | --- |
| Dataset | Video Game Sales |
| Source | Kaggle |
| Main variables | Name, Platform, Year, Genre, Publisher |
| Sales variables | NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales |
| Geographic coverage | North America, Europe, Japan, and Other Regions |
| Sales measurement | Millions of units |

**Dataset Source:** [Kaggle – Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)

---

## Data Processing & Methodology

The project follows a structured analytical workflow covering data preparation, exploratory analysis, statistical testing, and visualization.

### 1. Data Cleaning

- Identified missing values in the Year and Publisher columns.
- Removed incomplete records to improve data quality and maintain consistency.
- Converted data types to support accurate analysis.
- Checked for duplicate records and confirmed that no duplicates were found.

### 2. Exploratory Data Analysis

- Analyzed global sales distribution across genres, platforms, publishers, and regions.
- Identified top-performing publishers, genres, and gaming platforms.
- Explored historical trends in game releases and sales.
- Compared regional sales patterns to identify differences in market preferences.

### 3. Statistical Analysis

- Applied statistical testing to investigate differences in sales performance across platforms.
- Used SciPy to support quantitative analysis and interpretation.

### 4. Data Visualization

- Created exploratory visualizations using Matplotlib and Seaborn.
- Developed an interactive Tableau dashboard to communicate sales trends, regional comparisons, and key findings.

---

## Key Findings

### 1. Genre Performance

**Action is the best-performing genre globally.**

Action leads global sales, followed by Sports and Shooter. This indicates strong historical demand for these genres and highlights their importance in the overall gaming market.

### 2. Publisher Performance

**Nintendo dominates the publisher landscape.**

The analysis reveals that global video game sales are concentrated among a relatively small number of major publishers, with Nintendo standing out as a leading contributor.

### 3. Regional Market Preferences

**Regional preferences differ significantly across gaming markets.**

- **North America:** Xbox 360 performs strongly, closely followed by PlayStation 2.
- **Europe:** Platform performance is relatively balanced, with a slight advantage for PlayStation.
- **Japan:** Nintendo platforms are favored, while Xbox has a weaker presence.

These differences suggest that platform popularity is not uniform across regions.

### 4. Platform Performance

**Platform choice has a strong impact on sales performance.**

The analysis highlights differences in platform performance across geographic markets, reinforcing the importance of considering regional characteristics when planning game distribution.

---

## Dashboard

**Interactive Tableau Dashboard:** [View Dashboard](https://public.tableau.com/app/profile/nabilah.putri.intaka1611/viz/VideoGameSalesDashboard_17376436610220/Dashboard?publish=yes)

The dashboard provides an interactive overview of global video game sales from **1980 to 2020**, highlighting historical trends across platforms, genres, and regions.

### Dashboard Highlights

| Metric | Result |
| --- | --- |
| Total Games | 16,598 |
| Top Platform | PlayStation 2 (PS2) |
| Top Genre | Action |
| Peak Year | 2008 |

### Dashboard Visualizations

- Total Games by Year
- Top Platforms by Global Sales
- Sales by Genre
- Sales by Region
- Top Games by Global Sales

Users can explore sales distributions and historical trends to better understand the factors associated with video game market performance.

---

## Business Recommendations

### Genre Strategy

Prioritize further market research into high-performing genres such as Action, Sports, and Shooter, while considering differences in competition and audience demand.

### Regional Platform Strategy

Adapt platform selection to regional market characteristics rather than applying a uniform global distribution strategy.

### Market Segmentation

Use regional sales patterns to identify potential market opportunities and guide product positioning.

### Data-Driven Decision Making

Combine historical sales analysis with more recent market data, consumer preferences, and development costs before making investment decisions.

---

## Tools & Technologies

| Tool | Purpose |
| --- | --- |
| Python | Data processing and analysis |
| Pandas & NumPy | Data manipulation and numerical operations |
| Matplotlib & Seaborn | Exploratory data visualization |
| SciPy | Statistical analysis |
| Tableau | Interactive dashboard development |
| Jupyter Notebook | Analysis and documentation |

---

## Project Structure

- Data cleaning and analysis → Jupyter Notebook
- Statistical analysis → Python and SciPy
- Exploratory visualization → Matplotlib and Seaborn
- Interactive dashboard → Tableau
- Business insights → Findings and recommendations

---

## How to Use

1. Download or clone the repository.
2. Open the Jupyter Notebook to explore the data cleaning and analysis workflow.
3. Review the exploratory visualizations and statistical analysis.
4. Access the interactive Tableau dashboard through the link above.
5. Explore the key findings and business recommendations.

---

## Limitations

- The dataset only includes games with sales above 100,000 copies, which may exclude smaller or independent games.
- Historical sales data may not reflect recent developments in digital distribution and modern gaming platforms.
- The dataset does not include player behavior, marketing expenditure, or player demographics.
- The analysis focuses on historical sales patterns rather than predictive modeling.

---

## Future Improvements

- Develop predictive models to forecast video game sales.
- Perform deeper analysis of genre-platform combinations.
- Integrate additional datasets such as user reviews, ratings, and playtime.
- Analyze trends in modern platforms, including mobile gaming and digital distribution.


---

**Project:** Video Game Sales Analysis  
**Category:** Data Analytics / Exploratory Data Analysis  
**Tools:** Python, SciPy, Tableau  
**Dataset:** Historical Video Game Sales
