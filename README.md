# ⚾ Baseball Analytics with R

This repository contains a series of analytical labs and a final Shiny app project that explore and visualize Major League Baseball (MLB) data using R. The work involves regression modeling, non-parametric smoothing, cross-validation, and interactive dashboard design.

---

## 🧪 Lab Overview

### `lab1_exploratory_data_analysis.Rmd`
Perform exploratory data analysis using `dplyr` and `ggplot2`. Clean, summarize, and visualize player performance data.
- **Skills:** data wrangling, filtering, group-wise summarization, scatter/histogram plotting

### `lab2_linear_regression.Rmd`
Fit and interpret simple and multiple linear regression models using `lm()`. Evaluate model assumptions with residual diagnostics.
- **Skills:** regression modeling, residual analysis, model interpretation

### `lab3_polynomial_interaction.Rmd`
Explore non-linear relationships using polynomial regression and interaction terms. Compare model fits using ANOVA.
- **Skills:** higher-order regression, interaction modeling, hypothesis testing

### `lab4_nonparametric_regression.Rmd`
Apply smoothing techniques including kernel smoothing (`ksmooth`), smoothing splines, and LOESS to reveal data trends.
- **Skills:** non-parametric modeling, visualization of flexible fits

### `lab5_cross_validation.Rmd`
Use cross-validation to compare predictive performance across models. Assess overfitting/underfitting via MSE.
- **Skills:** k-fold CV, model selection, prediction error estimation

---

## 🚀 Final Project: MLB Performance Explorer (Shiny App)

An interactive Shiny dashboard for MLB data exploration, integrating historical stats from Lahman and pitch-level data from Statcast.

### 📊 Features:
- **Player Statistics**: Visualizes batting average over seasons by player
- **Heatmaps**: Generates pitch location density plots by pitch type
- **Team Comparison**: Compares team OPS across selected seasons
- **Historical Explorer**: Plots team wins, losses, and attendance over time

### 🛠️ Tech Stack:
- `R`, `Shiny`, `ggplot2`, `plotly`, `DT`, `dplyr`
- Datasets: `Lahman`, `baseballr`, `Statcast`

---

## 📈 Skills Demonstrated

- Exploratory data analysis & visualization
- Linear and non-linear regression modeling
- Model evaluation and selection via cross-validation
- Shiny dashboard design and deployment
- Integration of real-world sports datasets

---

> 🎓 Built as part of an applied statistics course at the University of Illinois Urbana-Champaign (Spring 2025)
