# Formula 1 Machine Learning Analysis

## Overview
This project explores **unsupervised** and **supervised learning** techniques applied to Formula 1 race data. The goal is to analyze driver performance, cluster drivers based on their characteristics, and predict future performance using real-world race data.

## Key Features
1. **Data Collection**:
   - Utilizes the [FastF1 API](https://theoehrly.github.io/Fast-F1/) to fetch structured race data from 2018 to 2023.
   - Implements caching to avoid redundant API calls.

2. **Unsupervised Learning**:
   - Clusters drivers based on performance metrics using **KMeans**.
   - Visualizes clusters using **PCA**.

3. **Supervised Learning**:
   - Predicts driver performance in future races.
   - Explores features like qualifying position, average lap time, and position changes.

4. **Exploratory Data Analysis (EDA)**:
   - Visualizes trends and correlations in driver performance.
   - Analyzes team and driver-specific statistics.

## Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
