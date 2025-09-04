# Stock-Market-Analysis-by-Sector

### 📈 Project Overview
This project conducts comprehensive analysis of stock market performance across various industry sectors to support sustainable investment decision-making. Using Exploratory Data Analysis (EDA) and statistical inference, we investigate sector behaviors, correlations, and performance metrics to identify promising opportunities for long-term investing.

---

### 🎯 Objectives
- **Correlation Analysis**: Analyze correlations between industry sectors' stock returns  
- **COVID-19 Impact**: Evaluate sector performance during key pandemic periods  
- **Risk Assessment**: Assess sectors' risk-adjusted returns over a 5-year period  
- **Investment Insights**: Identify stable and promising sectors for sustainable investing  

---

### 🔍 Research Questions

1. Which industry sectors exhibit the strongest correlations in their stock price returns?  
2. How did different sectors perform during key COVID-19 periods (pre-pandemic, pandemic onset, and recovery)?  
3. Which industry sectors offer the best risk-adjusted returns over 5 years?  

---

### 🛠️ Tools & Technologies

- **Python**  
- **Data Analysis**: pandas, numpy  
- **Visualization**: matplotlib, seaborn  
- **Statistical Analysis**: scipy, statsmodels

---

### 📊 Analysis Methodology
#### Exploratory Data Analysis (EDA)

- Summary statistics (mean, median, standard deviation)  
- Time series plotting and trend analysis  
- Sector-wise distribution analysis  
- Correlation heatmaps  
- Outlier detection using box plots
  
#### Statistical Inference
| #  | Research Question                                                                                           | Test                 | Reason                                                                                  |
| -- | ----------------------------------------------------------------------------------------------------------- | -------------------- | -------------------------------------------------------------------------------------------- |
| Q1 | Which industry sectors exhibit the strongest correlations in their stock price returns?                     | Spearman correlation | Assess strength and direction of monotonic relationships between sector return pairs         |
| Q2 | How did different sectors perform during key COVID-19 periods (pre-pandemic, pandemic onset, and recovery)? | Kruskal-Wallis test  | Compare sector returns across different COVID-19 periods (non-parametric test for 3+ groups) |
| Q3 | Which industry sectors offer the best risk-adjusted returns over 5 years                                    | Kruskal-Wallis test  | Compare Sharpe ratios across sectors to identify differences in risk-adjusted performance    |

