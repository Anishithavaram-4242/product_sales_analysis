# 🚀 E-Commerce Analytics Platform: Advanced Customer Insights & Sales Forecasting

<div align="center">

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Status](https://img.shields.io/badge/Status-Active-success.svg)

**A comprehensive data science project combining machine learning, statistical analysis, and business intelligence to extract actionable insights from e-commerce sales data.**

[![GitHub](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/Anishithavaram-4242?tab=repositories)

**Developed by:** [Anishitha Varma](https://github.com/Anishithavaram-4242)

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Features](#-key-features)
- [Technologies & Libraries](#-technologies--libraries)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [Usage](#-usage)
- [Key Insights & Deliverables](#-key-insights--deliverables)
- [Methodology](#-methodology)
- [Results & Visualizations](#-results--visualizations)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🎯 Project Overview

This project is a **comprehensive e-commerce analytics platform** that performs deep-dive analysis on electronics sales data. It combines exploratory data analysis, statistical modeling, machine learning algorithms, and business intelligence to extract actionable insights for strategic decision-making.

The platform addresses critical business questions such as:
- **Who are our customers?** (Customer segmentation)
- **What will sales look like in the future?** (Sales forecasting)
- **What products should we recommend?** (Recommendation system)
- **When are peak sales periods?** (Temporal analysis)
- **Which products perform best?** (Product performance analysis)

---

## ✨ Key Features

### 🔍 Advanced Data Preprocessing
- Automated data cleaning and validation pipelines
- Feature engineering (temporal features, customer engagement scores)
- Handling missing values and outliers
- Data type optimization and transformation

### 👥 Customer Segmentation
- **K-Means Clustering** to identify distinct customer groups
- Customer behavior analysis based on purchasing patterns
- Engagement scoring and customer lifetime value estimation
- Targeted marketing strategy recommendations

### 📈 Sales Forecasting
- **Time Series Analysis** with moving averages
- **Random Forest Regression** for predictive modeling
- Seasonal trend identification
- Future sales prediction with confidence intervals

### 🎯 Product Recommendation System
- **Collaborative Filtering** using cosine similarity
- User-item matrix construction
- Item-based recommendation engine
- Personalized product suggestions

### 📊 Statistical Analysis
- Correlation analysis and heatmaps
- Normality testing (Shapiro-Wilk test)
- Hypothesis testing
- Year-over-year performance comparison

### 📉 Interactive Visualizations
- Advanced data visualizations using Matplotlib and Seaborn
- Multi-panel dashboard-style charts
- Temporal trend analysis
- Category and brand performance comparisons

### 💼 Business Intelligence
- Actionable insights and strategic recommendations
- Peak sales period identification
- Product category performance metrics
- Customer satisfaction analysis

---

## 🛠 Technologies & Libraries

### Core Technologies
- **Python 3.8+**
- **Jupyter Notebook** for interactive analysis

### Data Manipulation
- `pandas` - Data manipulation and analysis
- `numpy` - Numerical computing

### Visualization
- `matplotlib` - Static visualizations
- `seaborn` - Statistical visualizations
- `plotly` - Interactive visualizations (optional)

### Machine Learning
- `scikit-learn` - ML algorithms:
  - K-Means Clustering
  - Random Forest Regressor
  - StandardScaler for feature scaling
  - Cosine Similarity for recommendations

### Statistical Analysis
- `scipy` - Statistical tests and functions
- `statsmodels` - Time series analysis (optional)

---

## 📁 Project Structure

```
Product_Analysis/
│
├── ECommerce_Customer_Analytics_ML.ipynb    # Main analysis notebook
├── electronics.csv                           # Raw dataset
├── electronics_cleaned.csv                   # Processed dataset
├── Amazon_Electronics_Products_Sales.zip     # Dataset archive
└── DASHBOARDS.pbix                          # Power BI dashboard (optional)
│
├── README.md                                 # Project documentation
├── requirements.txt                         # Python dependencies
└── .gitignore                               # Git ignore file
```

---

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)
- Jupyter Notebook or JupyterLab

### Step 1: Clone the Repository
```bash
git clone https://github.com/Anishithavaram-4242/[repository-name].git
cd [repository-name]
```

### Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```

Or install packages individually:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy jupyter ipykernel
```

### Step 3: Download Dataset
1. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/edusanketdk/electronics)
2. Place `electronics.csv` in the `Product_Analysis/` directory

---

## 💻 Usage

### Running the Analysis

1. **Start Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

2. **Open the Main Notebook**
   - Navigate to `Product_Analysis/ECommerce_Customer_Analytics_ML.ipynb`
   - Click to open in Jupyter

3. **Run All Cells**
   - Go to `Cell` → `Run All` to execute the entire analysis
   - Or run cells individually using `Shift + Enter`

4. **Review Results**
   - Visualizations will be displayed inline
   - Business insights are printed at the end
   - Export visualizations as needed

### Notebook Sections

The notebook is organized into 10 main sections:

1. **Data Loading and Initial Exploration**
2. **Data Preprocessing and Feature Engineering**
3. **Exploratory Data Analysis (EDA)**
4. **Customer Behavior Analysis**
5. **Customer Segmentation using K-Means Clustering**
6. **Sales Forecasting with Time Series Analysis**
7. **Statistical Analysis**
8. **Product Recommendation System (Collaborative Filtering)**
9. **Business Insights and Recommendations**
10. **Summary and Conclusions**

---

## 📊 Key Insights & Deliverables

### 1. Customer Behavior Analysis
- Identified distinct customer segments with unique purchasing patterns
- Calculated customer engagement scores
- Analyzed rating distributions and review patterns

### 2. Sales Trend Forecasting
- Predicted future sales trends using time series analysis
- Identified seasonal patterns and peak sales periods
- Built predictive models with performance metrics (MSE, R²)

### 3. Product Performance Metrics
- Analyzed top-performing products and categories
- Identified market leaders and underperformers
- Calculated category-wise sales distribution

### 4. Recommendation System
- Built collaborative filtering model for product recommendations
- Created item-item similarity matrix
- Implemented recommendation function for personalized suggestions

### 5. Business Recommendations
- Data-driven strategic recommendations for inventory management
- Marketing campaign timing suggestions
- Customer segmentation-based targeting strategies

---

## 🔬 Methodology

### Data Preprocessing
1. **Data Loading**: Import CSV data with proper encoding
2. **Data Cleaning**: Remove duplicates, handle missing values
3. **Feature Engineering**: 
   - Extract temporal features (year, month, quarter, day of week)
   - Create customer-level aggregations
   - Calculate engagement scores

### Machine Learning Pipeline
1. **Customer Segmentation**:
   - Feature selection and standardization
   - Elbow method for optimal cluster number
   - K-Means clustering implementation
   - Cluster interpretation and visualization

2. **Sales Forecasting**:
   - Time series data preparation
   - Moving average calculation
   - Feature engineering for regression
   - Random Forest model training and evaluation

3. **Recommendation System**:
   - User-item matrix construction
   - Cosine similarity calculation
   - Item-based collaborative filtering
   - Recommendation generation

### Statistical Analysis
- Correlation analysis between numerical features
- Normality testing for rating distribution
- Year-over-year performance comparison
- Hypothesis testing where applicable

---

## 📈 Results & Visualizations

The analysis generates comprehensive visualizations including:

- **Rating Distribution**: Histograms and box plots
- **Temporal Trends**: Sales by year, month, quarter
- **Category Analysis**: Top categories with horizontal bar charts
- **Customer Segmentation**: Scatter plots showing cluster distributions
- **Sales Forecasting**: Time series plots with predictions
- **Correlation Heatmaps**: Feature correlation matrices
- **Business Insights**: Summary statistics and recommendations

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

## 👤 Author

**Anishitha Varma**

- GitHub: [@Anishithavaram-4242](https://github.com/Anishithavaram-4242)
- Profile: [View Profile](https://github.com/Anishithavaram-4242?tab=repositories)

---

## 📞 Contact

For questions, suggestions, or collaborations:

- **GitHub**: [Anishithavaram-4242](https://github.com/Anishithavaram-4242)
- **Repository**: [View All Repositories](https://github.com/Anishithavaram-4242?tab=repositories)

---

## 🙏 Acknowledgments

- Dataset provided by [Kaggle](https://www.kaggle.com/datasets/edusanketdk/electronics)
- Built with Python data science ecosystem
- Inspired by real-world e-commerce analytics challenges

---

<div align="center">

**⭐ If you find this project helpful, please consider giving it a star! ⭐**

Made with ❤️ by [Anishitha Varma](https://github.com/Anishithavaram-4242)

</div>
