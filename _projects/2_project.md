---
layout: page
title: PUBG Win Rate Prediction & Data Analysis
subtitle: Python, Machine Learning, Data Visualization, Statistical Modeling
permalink: /projects/2_project/
thumbnail: assets/img/pubg.jpg
---

**PUBG Win Rate Prediction & Data Analysis** is a comprehensive data science project analyzing over **4.4 million PUBG match records** to understand what factors contribute to winning in the world's most popular battle royale game.

## 📊 Project Overview

This project examines player behavior patterns across different game modes (Solo, Duo, Squad) to identify key performance indicators and build predictive models for win probability. The analysis reveals fascinating insights about player strategies and winning patterns.

## 🔍 Key Findings

### Winning Strategies by Game Mode

| Game Mode | Best Strategy | Win Rate Impact |
|-----------|---------------|-----------------|
| **Solo** | Aggressive kills + Movement | High correlation with kills |
| **Duo** | Team coordination + Kills | Balanced approach |
| **Squad** | Team support + Survival | Kills less important than teamwork |

### Top Win Rate Predictors

1. **Walking Distance** (Highest positive correlation)
2. **Boost Items Used** (Strong positive correlation)
3. **Healing Items Used** (Moderate positive correlation)
4. **Kill Placement** (Highest negative correlation)
5. **Swimming Distance** (Surprisingly strong correlation)

## 🎯 What Makes a PUBG Winner?

The analysis reveals fascinating insights about player strategies:
- **The Killers**: Only 0.37% of players win without a single kill
- **The Runners**: Walking distance has the highest correlation with win rate
- **The Drivers**: Vehicle usage shows moderate correlation with success
- **The Swimmers**: Swimming ability correlates strongly with victory
- **The Healers**: Boost items are more valuable than healing items

## 📈 Data Structure

The dataset contains **29 features** across **4.4 million match records**:

### Core Gameplay Metrics
- **kills** - Number of enemy players eliminated
- **walkDistance** - Distance traveled on foot (meters)
- **rideDistance** - Distance traveled in vehicles (meters)
- **swimDistance** - Distance traveled swimming (meters)
- **damageDealt** - Total damage inflicted
- **heals** - Number of healing items used
- **boosts** - Number of boost items used

### Team-Based Features
- **assists** - Enemy players damaged but killed by teammates
- **DBNOs** - Enemy players knocked (Duo/Squad only)
- **revives** - Teammates revived (Duo/Squad only)
- **teamKills** - Friendly fire incidents

## 🛠️ Technical Implementation

### Data Analysis Pipeline
- **Data Cleaning**: Handling missing values and outliers
- **Feature Engineering**: Creating derived features and correlations
- **Statistical Analysis**: Correlation studies and hypothesis testing
- **Visualization**: Rich visualizations using Seaborn and Matplotlib
- **Model Development**: Machine learning models for win prediction

### Visualizations Created
- **Kill distribution** histograms
- **Movement correlation** joint plots
- **Game mode comparison** point plots
- **Feature correlation** heatmaps
- **Strategy effectiveness** box plots

## 💻 Technical Stack

- **Language**: Python 3.7+
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn
- **Environment**: Jupyter Notebook
- **Analysis**: Statistical modeling, correlation analysis

## 🎯 Learning Outcomes

This project demonstrates:
- **Large-scale data analysis** with 4.4M+ records
- **Statistical modeling** and correlation studies
- **Data visualization** best practices
- **Machine learning** insights for gaming analytics
- **Cross-mode analysis** and comparative studies

[View Project on GitHub](https://github.com/virtual457/Data-analysis-on-pubg){: .btn .btn-primary .btn-sm}
[View Analysis Notebook](https://github.com/virtual457/Data-analysis-on-pubg/blob/master/python.ipynb){: .btn .btn-outline-primary .btn-sm}
