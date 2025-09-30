# 📊 Customer Churn Analysis

Using machine learning to predict which customers are likely to leave.

---

## 📝 Project Overview

Analyzes telecommunications customer data to understand churn patterns and build a predictive model.

- **7,043 customers** with service, contract, and billing data
- **26.5% churn rate** identified
- **80% model accuracy** achieved with Random Forest
- **$139,000+ monthly revenue loss** from churned customers

## 📊 Key Findings

### Contract Types (Biggest Factor)
- Month-to-month: **42.7% churn rate**
- One year: **11.3% churn rate**  
- Two year: **2.8% churn rate**

### Payment Methods
- Electronic check: **45.3% churn rate** (highest risk)
- Credit card: **15.2% churn rate**
- Bank transfer: **16.2% churn rate**

### Customer Demographics
- Senior citizens: **41.7% churn rate**
- Customers without partners: **32.9% churn rate**
- New customers: highest risk group

## 🤖 Machine Learning Results

- **Model**: Random Forest Classifier
- **Accuracy**: 80%
- **AUC Score**: 0.8406
- **High-risk customers identified**: 109 customers
- **Top predictive factors**: Tenure, Total Charges, Monthly Charges, Contract Type

## 💡 Recommendations

1. **Focus on contracts**: Encourage longer-term contracts
2. **Fix payment issues**: Migrate electronic check users to automatic payments  
3. **Improve fiber service**: Address quality problems (30.9% churn rate)
4. **Support new customers**: Extra attention in first few months
5. **Target high-risk customers**: Use ML model for proactive retention

## 🚀 Quick Start

1. **Setup environment:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   ```

2. **Run analysis:**
   ```bash
   jupyter notebook Churn_analysis.ipynb
   ```

3. **View results:**
   - Charts saved to `figures/` folder
   - Model identifies high-risk customers
   - Financial impact calculated

## 📁 Files

- `Churn_analysis.ipynb` - Main analysis notebook
- `Customer-Churn.csv` - Dataset (7,043 records)
- `requirements.txt` - Dependencies (pandas, numpy, matplotlib, sklearn)
- `figures/` - Generated visualizations

---

**Competition Entry**: Data Analytics with AI – Contest #1 | **Date**: September 30, 2025
