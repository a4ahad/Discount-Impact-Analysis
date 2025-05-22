# 📊 Discount Impact Analysis

[![R](https://img.shields.io/badge/R-4.3.2-blue.svg)](https://www.r-project.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Analyzing the relationship between product discounts and customer reviews for Nike/Adidas products.

## 🔍 Project Overview
- **Hypothesis**: Do product discounts influence customer engagement (reviews)?
- **Dataset**: [Nike vs Adidas from Kaggle](https://www.kaggle.com/datasets/mariyamalshatta/nike-vs-addidas-unspervised-clustering)
- **Key Findings**:
  - Weak positive correlation (r = 0.296) 
  - Significant mean difference in reviews (p < 0.001)
  - High-discount products had 42.7 more reviews on average

## 📂 Repository Structure

```
Discount-Impact-Analysis/
├── LICENSE.md # Project license information
├── README.md # Project documentation
├── analysis/ # Analysis-related files
│   ├── analysis.Rmd # Full R Markdown analysis
│   ├── analysis.html # HTML output of the analysis
├── data/ # Dataset (consider gitignoring)
│   ├── nike_vs_addidas.csv # Dataset file
├── plots/ # Generated visualizations
│   ├── boxplot.png # Boxplot visualization
│   ├── density.png # Density plot visualization
│   ├── histogram.png # Histogram visualization
│   ├── scatter.png # Scatter plot visualization

```

## 🛠️ Installation & Usage
```bash
# Clone repository
git clone https://github.com/a4ahad/Discount-Impact-Reviews-Analysis.git

# Install dependencies
install.packages(c("ggplot2", "dplyr", "tidyr", "kableExtra"))
```

## 📈 Key Visualizations

## 📈 Key Visualizations

| Histogram        | Scatter Plot        |
|-----------------|---------------------|
| ![Discount Distribution](plots/histogram.png) | ![Correlation](plots/scatter.png) |

| Boxplot         | Density Plot        |
|-----------------|---------------------|
| ![Boxplot](plots/boxplot.png) | ![Density Plot](plots/density.png) |




## 📌 Results Summary

- **Statistical Significance:** `p < 2.2e-16 (t = 9.127)`
- **Practical Impact:** `+43 reviews per 10% discount increase`
- **Recommendation:** **Target 15-20% discounts** for optimal ROI

## 📄 License

**MIT License** - See [LICENSE](./LICENSE) for details

## 🌐 Connect

[LinkedIn Profile](https://www.linkedin.com/in/md-abdul-ahad-62b050305/)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
