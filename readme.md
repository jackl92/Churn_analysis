<h1 align="center">Customer Churn Analysis</h1>

<p align="center">A data analysis project exploring customer churn patterns in telecommunications data using Python and data visualization.</p>

---

## Project Overview

This project analyzes a telecommunications customer dataset to understand churn patterns and identify key factors that influence customer retention. The analysis uses exploratory data analysis and visualization techniques to uncover insights about customer behavior.

## Project Structure

```
Churn_analysis/
├── Churn_analysis.ipynb       # Main analysis notebook
├── Customer-Churn.csv         # Dataset (7,043 customer records)
├── requirements.txt           # Python dependencies
├── figures/                   # Generated visualization charts
└── README.md                 # Project documentation
```

## Dataset Information

<table>
  <tr>
    <th>Dataset</th>
    <td>Customer-Churn.csv</td>
  </tr>
  <tr>
    <th>Records</th>
    <td>7,043 customers</td>
  </tr>
  <tr>
    <th>Features</th>
    <td>20 columns including demographics, services, and billing info</td>
  </tr>
  <tr>
    <th>Target Variable</th>
    <td>Churn (Yes/No)</td>
  </tr>
</table>

### Key Features Analyzed

<ul>
  <li><strong>Demographics:</strong> Gender, Senior Citizen status, Partner, Dependents</li>
  <li><strong>Services:</strong> Internet Service, Streaming TV/Movies, Phone Service</li>
  <li><strong>Account Info:</strong> Contract type, Payment method, Monthly charges, Tenure</li>
  <li><strong>Billing:</strong> Paperless billing, Total charges</li>
</ul>

## Analysis Performed

### 1. Data Exploration
- Dataset overview and structure analysis
- Data cleaning and preprocessing
- Senior citizen status conversion for better readability

### 2. Churn Rate Analysis
The analysis examines churn rates across multiple dimensions:

<ul>
  <li><strong>Overall churn rate</strong> calculation</li>
  <li><strong>Gender-based</strong> churn comparison</li>
  <li><strong>Senior citizen</strong> churn patterns</li>
  <li><strong>Partner status</strong> impact on churn</li>
  <li><strong>Dependents</strong> influence on retention</li>
  <li><strong>Monthly charges</strong> categorized into tiers (Low: $0-50, Medium: $50-100, High: $100+)</li>
  <li><strong>Payment method</strong> preferences and churn correlation</li>
  <li><strong>Contract type</strong> impact on customer retention</li>
  <li><strong>Service usage</strong> patterns (Internet service, Streaming services)</li>
</ul>

### 3. Visualizations Generated

The analysis produces 12 comprehensive charts saved in the `figures/` directory:

<ul>
  <li>Overall customer churn distribution</li>
  <li>Churn by gender</li>
  <li>Churn by senior citizen status</li>
  <li>Churn by partner status</li>
  <li>Churn by dependents status</li>
  <li>Churn by monthly charge tiers</li>
  <li>Churn by payment method</li>
  <li>Churn by paperless billing status</li>
  <li>Churn by contract type</li>
  <li>Churn by internet service type</li>
  <li>Churn by streaming movies service</li>
  <li>Churn by streaming TV service</li>
</ul>

## Setup Instructions

### Prerequisites
- Python 3.8+
- Virtual environment (recommended)

### Installation

1. **Clone the repository and navigate to the directory:**
   ```bash
   cd Churn_analysis
   ```

2. **Create and activate virtual environment:**
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate  # On macOS/Linux
   ```

3. **Install required packages:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook Churn_analysis.ipynb
   ```

## Technologies Used

<ul>
  <li><strong>pandas</strong> - Data manipulation and analysis</li>
  <li><strong>numpy</strong> - Numerical computing</li>
  <li><strong>matplotlib</strong> - Data visualization and plotting</li>
  <li><strong>Jupyter Notebook</strong> - Interactive development environment</li>
</ul>

## Key Features

<ul>
  <li><strong>Automated chart saving:</strong> All visualizations are automatically saved to the figures/ directory</li>
  <li><strong>Comprehensive analysis:</strong> Covers demographic, service, and billing factors</li>
  <li><strong>Clean visualizations:</strong> Professional charts with consistent styling</li>
  <li><strong>Percentage calculations:</strong> Churn rates calculated for each category</li>
</ul>

## Usage

1. Open the Jupyter notebook
2. Run cells sequentially to reproduce the analysis
3. Generated charts will be saved automatically in the `figures/` folder
4. Modify charge tier thresholds or add new analysis as needed

## Results

The analysis provides insights into customer churn patterns across various dimensions, helping identify high-risk customer segments and potential retention strategies. All visualizations are generated as PNG files for easy sharing and presentation.

---

<p align="center"><em>Built for telecommunications customer retention analysis</em></p>
