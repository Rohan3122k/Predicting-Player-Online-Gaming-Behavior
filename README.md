# Predicting Player Online Gaming Behavior

### Project Overview

This project aims to predict player engagement in online gaming environments, particularly focusing on Steam games. The analysis identifies key factors driving player engagement, distinguishing high-value players, and recognizing cross-genre patterns affecting player retention.

### Objective

* Predict sustained player engagement using demographic, behavioral, and game-specific metrics.
* Identify attributes distinguishing high-value players (those making in-game purchases).
* Explore universal and genre-specific player engagement patterns.

### Data Sources

* **Predict Online Gaming Behavior Dataset:** Includes player demographics, gameplay patterns, and achievement data.
* **Steam Games Dataset:** Contains metadata, historical player statistics, rating patterns, and pricing information.

### Key Attributes Analyzed

**Player Demographics:**

* Age, Gender, Location

**Game-Specific Attributes:**

* Game Genre, Difficulty, Player Level, Achievements Unlocked

**Engagement Metrics:**

* Play Time (hours), In-game Purchases, Sessions per Week, Avg Session Duration (minutes)

### Methodology

* Data preprocessing including handling missing values and feature encoding (one-hot encoding)
* Exploratory data analysis (EDA) highlighting feature distributions, outliers, and correlations
* Model Development:

  * Logistic Regression
  * Random Forest
  * K-Nearest Neighbors (KNN)
  * Multi-Layer Perceptron (MLP)

### Model Performance Summary

| Model                  | Accuracy (%) | Weighted F1 Score |
| ---------------------- | ------------ | ----------------- |
| Random Forest          | 94.9         | 0.9487            |
| Multi-Layer Perceptron | 94.3         | 0.9428            |
| Logistic Regression    | 92.8         | 0.9270            |
| K-Nearest Neighbors    | 91.6         | 0.9026            |

### Key Findings

* **Strongest predictors:** Frequency and duration of gaming sessions.
* **Significant but moderate predictors:** Achievements and player level.
* **Notable regional engagement patterns:** Customized content strategy recommended.
* **Preferred game difficulty:** Majority favored easier game settings, recommending adjustable difficulty.

### Recommendations for Game Developers

* **Session Optimization:** Implement loops encouraging regular and extended play sessions.
* **Regional Customization:** Adjust content timing and promotions according to regional preferences.
* **Balanced Progression:** Design clear, rewarding progression pathways.
* **Adaptive Difficulty:** Incorporate responsive difficulty adjustments.
* **Data Analytics:** Utilize Random Forest models for ongoing engagement prediction.
* **Monetization:** Align monetization with engagement patterns without disrupting gameplay.
* **Community Building:** Foster strong community interaction to enhance social retention.
* **Content Strategy:** Develop predictable content release schedules to drive player anticipation and consistent engagement.

### Limitations

* Cross-sectional data restricts analysis of temporal engagement evolution.
* Correlation does not imply causation; additional controlled experiments are needed.
* Exclusion of external factors like social dynamics and competitive market conditions.

### Future Directions

* Integrate longitudinal data for temporal analysis.
* Conduct A/B testing for causal relationship verification.
* Employ social network analysis to evaluate community dynamics.
* Incorporate external event data for more comprehensive analysis.

### Conclusion

Employing the insights and methodologies detailed in this project can significantly enhance player engagement strategies and monetization efficiency, thus supporting sustainable growth in the competitive gaming industry.

---

© 2025 Northeastern University | Data Analytics Project
