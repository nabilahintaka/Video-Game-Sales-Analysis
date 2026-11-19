
# Video Game Sales Analysis

**Python-Based Data Analysis & Tableau Dashboard | Global Video Game Sales**

## Overview

This project analyzes global video game sales data to uncover patterns across genre, platform, publisher, and region. The goal is to generate actionable insights for better decision making.

## Executive Summary

The video game industry is highly concentrated, with a few publishers dominating global sales. Success is driven by genre, platform, and regional trends; specifically, Action games lead global demand, while platform preferences vary by location.

To maximize commercial impact, developers must abandon "one-size-fits-all" approaches in favor of data-driven, market-specific strategies.

---

## Business Objectives

- Identify the best-performing video game genres, platforms, and publishers.
- Analyze historical trends in game releases and sales.
- Compare regional market preferences and platform performance.
- Investigate differences in sales performance across platforms.
- Provide data-driven recommendations for game development and market targeting.

---

## Dataset

The project uses a historical video game sales dataset containing game titles, release years, platforms, genres, publishers, and regional sales figures.

| Attribute | Description |
| --- | --- |
| Dataset | Video Game Sales |
| Source | Kaggle |
| Coverage | Historical global video game sales |
| Sales regions | North America, Europe, Japan, and Other Regions |
| Main dimensions | Genre, Platform, Publisher, Year |
| Sales measurement | Millions of units |

**Dataset Source:** [Kaggle – Video Game Sales Dataset](https://www.kaggle.com/datasets/gregorut/videogamesales)

---

## Data Processing & Methodology

The project follows a structured analytical workflow, from data preparation to statistical analysis and visualization.

### 1. Data Cleaning

- Identified missing values in the Year and Publisher columns.
- Removed incomplete records to maintain consistency.
- Converted data types to support accurate analysis.
- Checked for duplicate records and validated dataset integrity.

### 2. Exploratory Data Analysis

- Examined global sales distribution across genres, platforms, publishers, and regions.
- Analyzed historical trends in game releases and sales.
- Compared regional market preferences and platform performance.

### 3. Statistical Analysis

- Applied statistical testing to investigate differences in sales performance across platforms.
- Used SciPy to support quantitative analysis.

### 4. Data Visualization

- Created exploratory visualizations using Matplotlib and Seaborn.
- Developed an interactive Tableau dashboard to communicate analytical findings.

---

## Key Insights

### 1. Genre Performance

**Action is the best-performing genre globally.**

Action leads global sales, followed by Sports and Shooter, indicating strong historical demand for fast-paced games.

### 2. Publisher Performance

**Nintendo dominates the publisher landscape.**

The analysis highlights the concentration of global video game sales among leading publishers.

### 3. Regional Market Preferences

**Regional preferences differ significantly.**

- North America: Xbox 360 leads, closely followed by PlayStation 2.
- Europe: Platform performance is relatively balanced, with a slight PlayStation advantage.
- Japan: Nintendo platforms are favored, while Xbox has a weaker presence.

These differences highlight the importance of market-specific platform strategies.

### 4. Platform Performance

**Platform choice has a strong impact on sales performance.**

Sales performance varies across platforms and regions, indicating that platform selection should consider regional market characteristics.

---

## Dashboard

**Live Tableau Dashboard:** [View Interactive Dashboard](https://public.tableau.com/app/profile/nabilah.putri.intaka1611/viz/VideoGameSalesDashboard_17376436610220/Dashboard?publish=yes)

<p align="center">
  <img src="dashboard.png" width="800"/>
</p>

The interactive Tableau dashboard provides an overview of global video game sales from 1980 to 2020, highlighting key trends across platforms, genres, and regions.

### Dashboard KPIs

| Metric | Value |
| --- | --- |
| Total Global Sales | 8.92 million units |
| Total Games | 16,598 |
| Top Platform | PlayStation 2 |
| Top Genre | Action |
| Peak Year | 2008 |

### Dashboard Visualizations

- Total Games by Year
- Top Platforms by Global Sales
- Sales by Genre
- Sales by Region
- Top Games by Global Sales

Users can explore sales performance through interactive filters for year, genre, and platform.

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
| SciPy | Statistical testing |
| Tableau | Interactive dashboard development |
| Jupyter Notebook | Analysis and documentation |

---

## Project Structure

- Data cleaning and exploratory analysis → Jupyter Notebook
- Statistical analysis → Python and SciPy
- Data visualization → Matplotlib, Seaborn, and Tableau
- Business insights → Findings and recommendations

---

## How to Use

1. Download or clone this repository.
2. Open the Jupyter Notebook to review the data cleaning and exploratory analysis.
3. Explore the statistical analysis and visualizations.
4. Access the interactive Tableau dashboard using the link above.
5. Review the key insights and business recommendations.

---

## Limitations

- The dataset only includes games with sales above 100,000 copies, which may exclude smaller or independent games.
- Historical data may not reflect recent trends in digital distribution and modern gaming platforms.
- The dataset does not include user behavior, marketing expenditure, or player demographics.
- The analysis focuses on historical data rather than predictive modeling.

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
