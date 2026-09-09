# Seasonal Agriculture Performance Analysis

## VOIS × AICTE Internship — Major Project

A data-driven analysis of seasonal agricultural performance across crops, regions, farming practices, environmental conditions, resource usage, and economic outcomes.

---

## 📌 Project Overview

Agricultural performance varies significantly across seasons due to changes in environmental conditions, farming practices, resource availability, crop selection, and market conditions.

This project analyzes a seasonal agriculture performance dataset to identify:

- Seasonal patterns in crop yield and production
- Differences in agricultural performance across crops
- Relationships between environmental conditions and yield
- Impact of irrigation methods on agricultural performance
- Resource usage and water efficiency
- Seasonal disease and pest risks
- Crop-wise profitability
- Unusual patterns and data-quality issues
- Insights that can support evidence-based agricultural planning

The complete analysis is implemented using **Python in a Jupyter Notebook**.

---

## 🎯 Problem Statement

The objective is to analyze agricultural activities across different seasons and geographical areas to understand variations in agricultural performance.

The analysis considers:

- Crop production
- Yield
- Rainfall
- Temperature
- Humidity
- Soil conditions
- Fertilizer and pesticide usage
- Irrigation methods
- Water usage
- Disease and pest risk
- Market price
- Cost
- Revenue
- Profit

The project aims to discover meaningful seasonal patterns, relationships, variations, and unusual observations that can help support better agricultural decision-making.

---

## 🎯 Objectives

1. Explore and understand the agricultural dataset.
2. Clean and prepare the data for analysis.
3. Examine seasonal variations in agricultural performance.
4. Identify crop-wise and season-wise performance patterns.
5. Investigate relationships between environmental conditions and crop yield.
6. Compare different irrigation methods.
7. Analyze resource usage and water efficiency.
8. Study disease and pest risk across seasons.
9. Analyze crop-wise economic performance and profitability.
10. Identify unusual patterns and potential data-quality issues.
11. Apply appropriate statistical and visualization techniques.
12. Develop evidence-based conclusions and recommendations.

---

## 📊 Dataset

The dataset contains **4,000 agricultural records and 28 variables**.

It represents agricultural activities across different:

- States
- Districts
- Crops
- Seasons
- Environmental conditions
- Soil conditions
- Farming practices
- Resource usage
- Production metrics
- Economic indicators

### Major Dataset Attributes

| Category | Variables |
|---|---|
| Farm Information | Farm Area, State, District |
| Crop Information | Crop, Season |
| Environmental Factors | Rainfall, Temperature, Humidity, Sunlight |
| Soil Conditions | Soil pH, Soil Moisture |
| Nutrients | Nitrogen, Phosphorus, Potassium |
| Farm Inputs | Fertilizer, Pesticide, Seed Quality |
| Irrigation | Irrigation Method, Water Used |
| Production | Yield, Production |
| Economic Factors | Market Price, Cost, Revenue, Profit |
| Efficiency | Water Efficiency |
| Risk | Disease/Pest Risk |

---

## 🌾 Dataset Categories

### States

- Andhra Pradesh
- Telangana
- Maharashtra
- Madhya Pradesh
- Karnataka
- Gujarat
- Tamil Nadu
- Punjab

### Crops

- Rice
- Wheat
- Maize
- Cotton
- Pulses
- Groundnut
- Chilli
- Sugarcane

### Seasons

- **Kharif**
- **Rabi**
- **Zaid**

### Irrigation Methods

- Flood
- Rainfed
- Drip
- Sprinkler

---

# 🔬 Methodology

```text
Dataset
   ↓
Data Loading
   ↓
Data Understanding
   ↓
Data Quality Checks
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Seasonal Analysis
   ↓
Crop & Season Analysis
   ↓
Irrigation Analysis
   ↓
Environmental Analysis
   ↓
Risk Analysis
   ↓
Profitability Analysis
   ↓
Statistical Testing
   ↓
Key Findings
   ↓
Recommendations
   ↓
Conclusion
```

---

# 🧹 Data Preparation

The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Numeric ranges
- Categorical distributions
- Potential inconsistencies

Missing observations were identified in:

- Rainfall
- Soil Moisture
- Yield

There were **no duplicate rows** in the dataset.

Missing values are handled during analysis without unnecessarily altering the original dataset.

---

# 📈 Exploratory Data Analysis

The notebook performs exploratory analysis to understand the structure and distribution of the data.

The analysis includes:

- Dataset dimensions
- Data types
- Summary statistics
- Missing-value analysis
- Duplicate checking
- Categorical distributions
- Numeric distributions
- Crop distributions
- Season distributions
- Irrigation-method distributions

---

# 🌦️ Seasonal Performance Analysis

Agricultural performance was compared across:

- Kharif
- Rabi
- Zaid

The analysis focuses on:

- Yield
- Production
- Revenue
- Cost
- Profit
- Water usage
- Water efficiency
- Disease/Pest risk

### Average Seasonal Performance

| Metric | Kharif | Rabi | Zaid |
|---|---:|---:|---:|
| Yield (t/ha) | 5.64 | 5.08 | 4.67 |
| Production (t) | 46.31 | 41.49 | 38.89 |
| Revenue | ₹7.11 L | ₹6.02 L | ₹5.19 L |
| Cost | ₹5.32 L | ₹5.14 L | ₹5.44 L |
| Profit | ₹1.79 L | ₹0.88 L | -₹0.25 L |
| Water Used | 6102 m³ | 5847 m³ | 6420 m³ |
| Water Efficiency | 5.89 | 5.19 | 4.41 |
| Disease/Pest Risk | 54.47% | 40.48% | 38.22% |

### Key Observation

Kharif shows the strongest overall average agricultural performance, while Zaid records the weakest economic performance and negative average profit.

---

# 🌾 Crop × Season Analysis

Crop performance was analyzed across all three seasons using a crop-season comparison.

An important pattern observed in the dataset is:

> **For every analyzed crop, average yield follows the pattern Kharif > Rabi > Zaid.**

| Crop | Kharif | Rabi | Zaid |
|---|---:|---:|---:|
| Sugarcane | 53.46 | 43.94 | 38.42 |
| Maize | 2.97 | 2.61 | 2.30 |
| Rice | 2.71 | 2.33 | 1.90 |
| Wheat | 2.26 | 2.06 | 1.75 |
| Chilli | 1.73 | 1.46 | 1.18 |
| Groundnut | 1.48 | 1.22 | 1.04 |
| Cotton | 1.37 | 1.19 | 0.95 |
| Pulses | 1.04 | 0.87 | 0.65 |

---

# 💧 Irrigation Analysis

Different irrigation methods were compared based on agricultural performance.

### Average Yield by Irrigation Method

| Irrigation Method | Average Yield (t/ha) |
|---|---:|
| Drip | 6.62 |
| Sprinkler | 5.19 |
| Flood | 4.90 |
| Rainfed | 4.61 |

### Positive-Profit Share

| Irrigation Method | Profitable Farms |
|---|---:|
| Drip | 59.8% |
| Sprinkler | 51.9% |
| Flood | 47.2% |
| Rainfed | 46.9% |

### Key Observation

Drip irrigation has the highest average yield and the highest proportion of profitable farms in this dataset.

This demonstrates an association in the observed data and does **not** establish causation.

---

# 🌱 Environmental Factors

The relationship between environmental conditions and crop yield was examined using **Spearman correlation**.

Variables analyzed:

- Rainfall
- Soil moisture
- Humidity
- Average temperature
- Sunlight
- Soil pH

### Spearman Correlation with Yield

| Environmental Variable | Correlation with Yield |
|---|---:|
| Rainfall | 0.13 |
| Soil Moisture | 0.10 |
| Humidity | 0.08 |
| Average Temperature | ~0.00 |
| Sunlight | -0.05 |
| Soil pH | -0.03 |

### Key Observation

The correlations are relatively weak.

Rainfall and soil moisture show the strongest positive associations among the analyzed environmental variables, but the relationships are not strong enough to conclude that any individual environmental variable directly determines yield.

---

# 🐛 Disease & Pest Risk

Disease and pest risk was analyzed across seasons.

### Average Risk

| Season | Disease/Pest Risk |
|---|---:|
| Kharif | 54.47% |
| Rabi | 40.48% |
| Zaid | 38.22% |

### Key Observation

Kharif has the highest average disease/pest risk in the dataset.

This suggests that seasonal agricultural planning should include stronger crop monitoring and preventive measures during higher-risk periods.

---

# 💰 Crop Profitability Analysis

Economic performance was analyzed using average profit by crop.

| Crop | Average Profit |
|---|---:|
| Sugarcane | ₹8.17 L |
| Chilli | ₹7.51 L |
| Cotton | ₹1.25 L |
| Groundnut | ₹0.45 L |
| Pulses | -₹0.04 L |
| Maize | -₹0.84 L |
| Rice | -₹1.02 L |
| Wheat | -₹1.23 L |

### Key Observation

Sugarcane and chilli show the strongest average profitability in the dataset, while wheat, rice, and maize show negative average profit.

Economic performance should therefore be considered alongside yield when making crop-planning decisions.

---

# 📊 Statistical Analysis

Because yield is highly skewed in the dataset, a **Kruskal-Wallis test** was used to compare yield distributions across seasons.

### Result

- Test statistic: **H ≈ 68.60**
- p-value: **≈ 1.27 × 10⁻¹⁵**

The result indicates a statistically significant difference in yield distributions across seasons.

This supports the observed seasonal differences in yield.

### Important Note

Statistical significance does **not** establish causation. The result indicates that the distributions differ, not that season alone causes the observed differences.

---

# 🔎 Sugarcane Sensitivity Check

Sugarcane has substantially higher yield values than the other crops and strongly affects the overall average yield.

A sensitivity analysis was therefore performed by examining seasonal yield after excluding Sugarcane.

### Average Yield Excluding Sugarcane

| Season | Average Yield |
|---|---:|
| Kharif | 2.02 t/ha |
| Rabi | 1.75 t/ha |
| Zaid | 1.47 t/ha |

The same seasonal ordering remains:

**Kharif > Rabi > Zaid**

This indicates that the overall seasonal pattern is not solely caused by Sugarcane.

---

# ⚠️ Data Quality Considerations

The dataset contains some geographically unusual State–District combinations.

For example, certain districts appear alongside states where they would not normally be geographically located.

These observations were **not manually changed or deleted** because the project is intended to analyze the provided dataset.

Instead, this issue is documented as a data-quality limitation.

Therefore, conclusions involving geographical comparisons should be interpreted cautiously.

---

# ⚠️ Important Analytical Considerations

### 1. Correlation ≠ Causation

Observed relationships between variables do not prove that one variable causes another.

### 2. Yield Distribution is Highly Skewed

Sugarcane has substantially higher yield values than the other crops, which makes the overall mean sensitive to crop composition.

### 3. Water Efficiency is a Derived Metric

Water efficiency is mathematically related to yield and water usage.

Therefore, it should not be interpreted as a completely independent predictor of yield.

### 4. Dataset Quality

Geographical inconsistencies in State–District combinations may affect regional analysis.

---

# 💡 Key Findings

1. **Kharif performs best overall** in terms of average yield, production, revenue, profit, and water efficiency.

2. **Zaid shows the weakest economic performance**, with negative average profit.

3. **All analyzed crops show higher average yield in Kharif than Rabi and Zaid.**

4. **Drip irrigation has the highest average yield** among the irrigation methods analyzed.

5. **Drip irrigation also has the highest profitable-farm share.**

6. Environmental variables show **mostly weak correlations with yield**.

7. **Kharif has the highest disease/pest risk**, indicating the need for stronger seasonal monitoring.

8. **Sugarcane and chilli show the highest average profitability.**

9. Yield differences between seasons are statistically significant according to the Kruskal-Wallis test.

10. The seasonal yield pattern remains even after excluding Sugarcane.

---

# 💡 Recommendations

### 1. Strengthen Kharif Planning

Since Kharif demonstrates stronger overall performance, planning should focus on maximizing productivity while managing the higher disease/pest risk.

### 2. Improve Zaid Resource Management

Zaid shows lower yield, lower revenue, lower water efficiency, and negative average profit.

Resource allocation and crop selection should therefore be carefully evaluated for this season.

### 3. Promote Efficient Irrigation

Drip irrigation demonstrates stronger yield and profitability metrics in this dataset.

Where feasible, efficient irrigation systems can be evaluated as part of resource-management strategies.

### 4. Increase Pest Monitoring

The higher disease/pest risk observed in Kharif suggests the need for early detection and preventive crop-management practices.

### 5. Consider Crop Profitability

Crop selection should consider both productivity and economic performance rather than yield alone.

### 6. Improve Data Quality

Future agricultural datasets should maintain geographically consistent State–District mappings and complete environmental measurements.

---

# 🛠️ Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **SciPy**
- **Jupyter Notebook**
- **Google Colab**
- **Microsoft Excel**

---

# 📚 Analytical Techniques

The project uses:

- Descriptive statistics
- Missing-value analysis
- Duplicate detection
- Distribution analysis
- Group-by aggregation
- Seasonal comparison
- Crop-wise analysis
- Heatmaps
- Boxplots
- Bar charts
- Correlation analysis
- Spearman correlation
- Kruskal-Wallis statistical testing
- Sensitivity analysis
- Data-quality validation

---

# 📁 Repository Structure

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── data/
│   └── seasonal_agriculture_performance_dataset.xlsx
│
├── notebooks/
│   └── Seasonal_Agriculture_Performance_Analysis.ipynb
│
├── README.md
│
├── requirements.txt
│
└── .gitignore
```

---

# 🚀 How to Run the Project

## Option 1 — Google Colab

1. Open the Jupyter Notebook in the `notebooks` folder.
2. Upload the dataset from the `data` folder to Google Colab.
3. Make sure the dataset is available at:

```text
/content/seasonal_agriculture_performance_dataset.xlsx
```

4. Run the notebook cells sequentially.

---

## Option 2 — Local Jupyter Notebook

### Clone the repository

```bash
git clone https://github.com/<AmruthaRaju24>/Seasonal-Agriculture-Performance-Analysis.git
```

### Navigate into the project

```bash
cd Seasonal-Agriculture-Performance-Analysis
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
notebooks/Seasonal_Agriculture_Performance_Analysis.ipynb
```

For local execution, update the dataset path in the notebook to:

```text
../data/seasonal_agriculture_performance_dataset.xlsx
```

---

# 📦 Requirements

Main Python libraries:

```text
pandas
numpy
matplotlib
seaborn
scipy
openpyxl
jupyter
google colab
microsoft excel
```

Install using:

```bash
pip install -r requirements.txt
```

---

# 📓 Project Deliverables

The repository contains:

- Complete agricultural dataset
- Jupyter Notebook with the complete analysis
- Data-cleaning and validation procedures
- Exploratory data analysis
- Seasonal performance analysis
- Crop-season analysis
- Irrigation analysis
- Environmental analysis
- Disease/pest risk analysis
- Profitability analysis
- Statistical testing
- Key findings
- Recommendations
- Project documentation

---

# 🔮 Future Scope

The project can be extended with:

- Machine-learning-based yield prediction
- Crop recommendation systems
- Seasonal crop suitability prediction
- Weather forecasting integration
- Soil-based crop recommendations
- Regional agricultural dashboards
- Real-time agricultural data integration
- Time-series analysis using historical datasets
- Automated anomaly detection
- Predictive profitability analysis
- Water-demand prediction
- Disease and pest outbreak prediction

---

# 🏫 Internship Information

**Program:** VOIS for tech by EduNet Foundation  
**Project Type:** Major Project  
**Project:** Seasonal Agriculture Performance Analysis
**Author:** G AmruthaRaju

---

# 📜 Course Completion

The project is associated with the VOIS for tech by EDUNET foundation × AICTE internship learning requirements, including the **Data Visualization** course completion component.

---

# 📌 Conclusion

This project demonstrates how agricultural data can be analyzed to understand seasonal differences in productivity, resource utilization, environmental relationships, risk, and economic performance.

The analysis indicates that seasonal variation is an important factor in agricultural performance. Kharif generally demonstrates stronger performance, while Zaid presents comparatively weaker economic outcomes. Irrigation method, crop selection, environmental conditions, and disease/pest risk provide additional dimensions for understanding agricultural outcomes.

The findings can support evidence-based agricultural planning, resource management, crop selection, and future predictive analytics applications.

---

## ⭐ Project Highlights

- **4,000 agricultural records**
- **28 variables**
- **3 agricultural seasons**
- **8 major crops**
- **8 states**
- **4 irrigation methods**
- Seasonal performance analysis
- Crop × season analysis
- Irrigation comparison
- Environmental correlation analysis
- Disease/pest risk analysis
- Crop profitability analysis
- Statistical significance testing
- Sensitivity analysis
- Data-quality assessment

---

## 📂 Project Repository

**Repository Name:**

```text
Seasonal-Agriculture-Performance-Analysis
```

**GitHub Repository:**

```text
https://github.com/<AmruthaRaju24>/Seasonal-Agriculture-Performance-Analysis
```
