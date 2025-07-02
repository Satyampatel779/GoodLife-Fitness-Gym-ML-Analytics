# GoodLife Fitness - Machine Learning Analytics Project

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org)
[![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green.svg)](https://pandas.pydata.org)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange.svg)](https://matplotlib.org)
[![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Visualization-lightblue.svg)](https://seaborn.pydata.org)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine%20Learning-yellow.svg)](https://scikit-learn.org)

## 📋 Project Overview

This comprehensive data science project focuses on optimizing gym operations for GoodLife Fitness through advanced machine learning analytics. The project consists of two main analytical components designed to enhance facility utilization and improve customer experience.

### 🎯 Business Objectives

1. **Group Fitness Class Optimization**: Analyze and optimize group fitness class utilization patterns
2. **Gym Equipment Utilization Prediction**: Develop predictive models to forecast gym crowding patterns and encourage off-peak usage

## 📊 Project Components

### Part A: Group Fitness Class Utilization Analysis
- **Objective**: Optimize group fitness class scheduling and resource allocation
- **Dataset**: Comprehensive fitness class attendance data
- **Key Features**: 
  - Data preprocessing and missing value imputation
  - Exploratory Data Analysis (EDA) with correlation analysis
  - Statistical insights into class attendance patterns
  - Visualization of utilization trends

### Part B: Gym Equipment Utilization Prediction
- **Objective**: Predict gym crowding patterns to optimize facility usage
- **Dataset**: 26,000 observations of people counts over one year (10-minute intervals)
- **Key Features**:
  - `number_people`: Target variable (gym occupancy)
  - `date` & `timestamp`: Temporal features
  - `day_of_week` & `is_weekend`: Weekly patterns
  - `is_holiday`: Holiday effects
  - `temperature`: Weather impact
  - `is_start_of_semester` & `is_during_semester`: Academic calendar influence
  - `month` & `hour`: Seasonal and daily patterns

## 🛠️ Technical Stack

- **Programming Language**: Python 3.8+
- **Data Analysis**: Pandas, NumPy
- **Data Visualization**: Matplotlib, Seaborn
- **Machine Learning**: Scikit-learn
- **Development Environment**: Jupyter Notebook
- **Data Processing**: Statistical analysis, feature engineering, predictive modeling

## 📈 Key Analytical Approaches

### Data Preprocessing
- Missing value identification and imputation strategies
- Data type conversions and cleaning
- Feature engineering for temporal patterns

### Exploratory Data Analysis
- Distribution analysis of target variables
- Correlation heatmaps and statistical relationships
- Time-series pattern identification
- Seasonal and weekly trend analysis

### Predictive Modeling
- Time-series forecasting for gym occupancy
- Pattern recognition for optimal scheduling
- Statistical modeling for business insights

## 🎯 Business Impact

- **Operational Efficiency**: Optimize staff scheduling and resource allocation
- **Customer Experience**: Reduce overcrowding through predictive insights
- **Revenue Optimization**: Encourage off-peak usage through data-driven strategies
- **Facility Management**: Improve equipment maintenance scheduling

## 📁 Project Structure

```
GoodLife-Fitness-Gym-ML-Analytics/
├── development-part-a.ipynb          # Group fitness class analysis
├── Development part-b.ipynb          # Gym utilization prediction
└── README.md                         # Project documentation
```

## 🔍 Key Insights & Findings

### Group Fitness Classes (Part A)
- Comprehensive analysis of class attendance patterns
- Identification of optimal class scheduling windows
- Resource allocation recommendations

### Gym Utilization Patterns (Part B)
- Peak usage hours identification
- Seasonal and weekly attendance patterns
- Temperature and academic calendar impact analysis
- Holiday effects on gym usage

## 💼 Skills Demonstrated

- **Data Science**: End-to-end analytics pipeline development
- **Machine Learning**: Predictive modeling and time-series analysis
- **Business Analytics**: Translating data insights into actionable business strategies
- **Data Visualization**: Creating compelling visual narratives
- **Statistical Analysis**: Advanced statistical techniques for pattern recognition
- **Problem Solving**: Addressing real-world business challenges with data-driven solutions

## 🚀 Future Enhancements

- Real-time prediction dashboard
- Advanced machine learning models (ensemble methods, deep learning)
- Mobile app integration for user notifications
- A/B testing framework for optimization strategies
- Integration with gym management systems

## 📞 Contact

This project demonstrates proficiency in data science, machine learning, and business analytics, showcasing the ability to derive actionable insights from complex datasets to drive business value.

---

*This project was developed as part of a comprehensive data science portfolio, demonstrating expertise in machine learning applications for business optimization.*