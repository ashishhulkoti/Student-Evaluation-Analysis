# Student Evaluation Analysis

## Overview

This project aims to analyze student evaluation survey data collected from students in Turkey, employing clustering techniques to identify distinct patterns and insights into student feedback.

## Dataset

The dataset includes responses from students evaluating various aspects of their courses, instructors, and learning experiences. The features include:

- Instructor's teaching skills
- Course content relevance
- Communication effectiveness
- Instructor's engagement and supportiveness
- Overall satisfaction

## Objectives

- Analyze student evaluation data using exploratory data analysis (EDA)
- Implement clustering techniques (K-Means, Hierarchical clustering)
- Interpret clusters to gain insights into student feedback patterns

## Methodology

### Data Preparation

- Checked for null values and handled any missing data
- Conducted exploratory data analysis using visualizations (boxplots, histograms, heatmaps)

### Clustering Analysis

- Applied **K-Means clustering** algorithm to segment students into meaningful groups
- Evaluated the optimal number of clusters using the Elbow Method
- Performed **Hierarchical clustering** to confirm the findings

### Tools and Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Key Findings

- Identification of distinct student segments based on feedback
- Insights into attributes influencing student satisfaction and dissatisfaction
- Recommendations to improve teaching effectiveness and student satisfaction based on cluster insights

## Visualizations

Included visualizations:

- Cluster plots
- Dendrograms (Hierarchical clustering)
- Boxplots and histograms for data distribution

## Conclusion

Clustering analysis effectively highlighted key factors impacting student satisfaction, providing actionable insights for educators and administrators to enhance educational quality and student experience.

## How to Use

1. Clone the repository:

```bash
git clone [repository link]
```

2. Run the notebook:

```bash
jupyter notebook "Turkiye Student Evaluation Analysis - Clustering.ipynb"
```

