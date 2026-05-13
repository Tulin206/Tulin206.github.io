---
title: Baltic Sea Temperature and Salinity Prediction
date: 2024-10-26
tags:
  - Time Series
  - Machine Learning
  - LSTM
  - CNN
  - Environmental Data
  - Docker
featured: true
links:
  - type: dataset
    url: "https://www.balticsea.eu/"
---

## Project Overview

Developed an ML-based forecasting system to predict Baltic Sea temperature and salinity using two years of 6-hourly sampled data, surpassing traditional baseline methods.

<!--more-->

## Objective

Enhance predictions of Baltic Sea environmental conditions by leveraging temporal and spatial data patterns to outperform naive approaches (persistence, linear regression) with advanced ML models.

## Key Achievements

- **Model Architecture**: Hybrid LSTM + CNN approach for time series prediction
- **Data Processing**: Handled 6-hourly sampled temporal and spatial data over 2-year period
- **Performance**: Exceeded baseline methods significantly
- **Reproducibility**: Containerized solution using Docker for deployment

## Technical Approach

### Data Processing
- Time series data preparation and normalization
- Spatial feature extraction
- Temporal pattern analysis

### Model Architecture
- **LSTM Component**: Captures long-term temporal dependencies
- **CNN Component**: Extracts spatial features from oceanographic data
- **Hybrid Approach**: Combines strengths of both architectures

### Machine Learning Pipeline
- Feature engineering from raw environmental data
- Train/validation/test split with temporal considerations
- Hyperparameter optimization

## Technologies Used

**Languages & Frameworks**: Python, TensorFlow, Scikit-Learn

**Development Tools**: PyCharm, Jupyter Notebooks

**DevOps & Reproducibility**: Docker, CI/CD, DVC, Unit Testing

**Techniques**: Time Series Analysis, LSTM, CNN, Ensemble Methods

## Data Sources

- Real-life temporal and spatial data from Baltic Sea monitoring networks
- 6-hourly resolution over 24-month period
- Multiple environmental variables (temperature, salinity, currents)

## Impact

This project demonstrates the effectiveness of deep learning for environmental forecasting, with potential applications in:
- Ocean monitoring and prediction
- Climate research
- Environmental management
- Maritime operations planning

---

*Environmental data sourced from public Baltic Sea research networks and monitoring systems.*
