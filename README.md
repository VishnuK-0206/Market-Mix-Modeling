# Market
Mix Modeling

## 📊 Overview

Marketing Mix Modeling (MMM) is a statistical analysis technique that helps businesses:

- Estimate the impact of marketing tactics on sales  
- Predict future performance based on marketing strategies  
- Optimize marketing budget allocation across different channels  

The classic marketing mix consists of the **4 Ps**:

- **Product**: The offering or group of offerings to customers  
- **Price**: The amount customers pay for the product  
- **Place**: Distribution channels through which products reach customers  
- **Promotion**: Methods of communicating with customers (e.g., sales force, advertising, public relations)

Modern approaches extend this to include:

- **People**: Everyone who influences the perceived value  
- **Process**: Procedures that lead to value exchange  
- **Physical Evidence**: Sensory experiences that demonstrate value  

---

## 📁 Dataset

The dataset contains information about 27 vodka brands with the following key variables:

- Brand information (name, ID)  
- Sales metrics (total sales, dollar sales)  
- Price data (price per unit)  
- Advertising expenditures across channels:  
  - Magazine advertising  
  - Newspaper advertising  
  - Outdoor advertising  
  - Broadcast advertising  
  - Print advertising (Magazine + News)  
- Market positioning (Tier1/Tier2 brands)  
- Market share metrics  

> 📘 *Note: The dataset is sourced from the book* **"Cutting-Edge Marketing Analytics: Real World Cases and Data Sets for Hands-On Learning"**

---

## 📈 Analysis Approach

This repository demonstrates:

1. **Data exploration** to understand structure and relationships  
2. **Regression modeling** to quantify marketing impacts on sales  
3. **Price elasticity analysis** using log-transformed variables  
4. **Interaction effect analysis** between advertising channels  
5. **Model comparison** to evaluate predictive performance  

---

## 📌 Key Findings

The analysis for **Absolut** vodka reveals:

- **Price** significantly affects sales, explaining ~69% of the variance  
- **Incorporating advertising** variables increases model fit to **87%**  
- **Interaction effects** show synergies between **broadcast** and **print** advertising  

---

## 📦 Dependencies

To run the analysis, ensure the following Python libraries are installed:

- `pandas`  
- `numpy`  
- `matplotlib`  
- `seaborn`  
- `scikit-learn`  
- `statsmodels`

You can install them using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn statsmodels
