# 🏠 Iran House Price Analysis & Prediction

A comprehensive AI and data science project for analyzing and predicting housing prices in Iran using real-world real estate market data.

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green)
![Real Estate](https://img.shields.io/badge/Real-Estate-red)

## 📊 Overview

This project utilizes advanced data science and machine learning techniques to analyze factors influencing housing prices in Iran and predict future market trends. The solution provides valuable insights for investors, real estate professionals, and market analysts.

## 🎯 Objectives

- 🔍 Analyze key factors affecting housing prices in Iran
- 🤖 Build high-accuracy price prediction models
- 📈 Identify market patterns and trends
- 💡 Provide actionable insights for investment decisions
- 🏗️ Create a scalable framework for real estate analytics

## 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| **Programming** | Python 3.8+ |
| **Data Processing** | Pandas, NumPy |
| **Machine Learning** | Scikit-learn, XGBoost |
| **Data Visualization** | Matplotlib, Seaborn |
| **Development** | Jupyter Notebook |

## 📁 Project Structure

```
IranHouseValue/
├── HP_main.ipynb # Main analysis notebook
├── data/ # Project datasets
├── models/ # Trained ML models
├── README.md # Project documentation
└── requirements.txt # Dependencies
```

## 🚀 Quick Start

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Installation
```bash
# Clone repository
git clone https://github.com/SamyarZamani/IranHouseValue.git
cd IranHouseValue

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

## 📈 Dataset Features

The project uses comprehensive Iranian real estate data including:

- **Geographical Features** (District, Neighborhood, Location)
- **Physical Characteristics** (Area, Building Age, Room Count)
- **Amenities** (Parking, Storage, Elevator, Facilities)
- **Market Data** (Price per Square Meter, Transaction History)

## 🤖 Machine Learning Implementation

### Algorithms Deployed:
- **Linear Regression** - Baseline model
- **Decision Tree Regressor** - Non-linear relationships
- **Random Forest Regressor** - Ensemble method
- **Gradient Boosting** - High accuracy
- **XGBoost** - State-of-the-art performance

### Evaluation Metrics:
- **RMSE** (Root Mean Square Error)
- **MAE** (Mean Absolute Error)
- **R² Score** (Coefficient of Determination)
- **MAPE** (Mean Absolute Percentage Error)

## 💡 Key Findings

### Major Price Determinants:
- **Location** - Primary factor (80%+ impact)
- **Property Area** - Direct correlation with price
- **Building Age** - Inverse relationship
- **Amenities** - Value multipliers
- **Neighborhood Quality** - Social infrastructure

## 🎯 Model Performance

### Best Performing Model: XGBoost Regressor
- **Prediction Accuracy**: 87% (R² Score)
- **Average Error**: ±3.2 million Tomans
- **Investment Optimization**: Identified high-growth potential areas
- **Market Trend Prediction**: 3-month forecast capability

## 🏗️ Usage Examples

### For Price Prediction:
```python
from models.price_predictor import HousePricePredictor

# Load trained model
predictor = HousePricePredictor.load('models/best_model.pkl')

# Predict price for new property
prediction = predictor.predict({
    'area': 120,
    'district': 'Tehran District 1',
    'building_age': 5,
    'rooms': 3,
    'has_parking': True,
    'has_elevator': True
})
```
### For Model Development:
```python
# Add custom models
from sklearn.ensemble import RandomForestRegressor
from sklearn.model_selection import cross_val_score

model = RandomForestRegressor(n_estimators=200, random_state=42)
scores = cross_val_score(model, X_train, y_train, cv=5)
print(f"Cross-validation scores: {scores}")
```
## 📊 Business Applications

### Real Estate Agencies:
- **Accurate Property Valuation** - Automated price estimation for listings
- **Market Trend Analysis** - Identify emerging neighborhoods and price patterns
- **Investment Opportunity Identification** - Spot undervalued properties with high growth potential
- **Client Portfolio Optimization** - Data-driven recommendations for buyers and sellers

### Individual Investors:
- **Price Comparison Across Regions** - Cross-neighborhood and city-wide analysis
- **ROI Calculation & Forecasting** - Predict investment returns and appreciation rates
- **Market Entry Timing** - Optimal buying/selling periods based on historical trends
- **Risk Assessment** - Evaluate market volatility and investment security

### Government & Policy Makers:
- **Housing Market Monitoring** - Real-time tracking of market health and affordability
- **Economic Policy Impact Analysis** - Measure effects of regulations on housing prices
- **Urban Development Planning** - Data-driven decisions for infrastructure and zoning
- **Affordable Housing Initiatives** - Identify areas needing government intervention

## 🚀 Future Enhancements

- **Real-time Data Integration** - Live market data feeds and automated updates
- **Regional-Specific Models** - Customized algorithms for different Iranian provinces
- **Mobile Application** - User-friendly interface for on-the-go access
- **API Development** - RESTful API for third-party integrations
- **Time-Series Forecasting** - Advanced prediction of long-term market trends
- **Economic Indicator Integration** - Correlation with inflation, GDP, and employment data
- **Interactive Dashboard** - Visual analytics platform for business intelligence
- **Automated Report Generation** - Scheduled market insights and investment alerts

## 🤝 Contributing

We welcome contributions from the community! Whether you're a data scientist, developer, or real estate enthusiast, your input is valuable.

### Ways to Contribute:
- **Report Bugs and Issues** - Help improve project stability
- **Suggest Model Improvements** - Enhance prediction accuracy and performance
- **Add New Datasets** - Expand data coverage across different regions
- **Enhance Documentation** - Improve guides and code comments
- **Develop New Features** - Add innovative functionalities
- **Translate Content** - Make the project accessible to Persian speakers
- **Optimize Code** - Improve efficiency and scalability

### Contribution Process:
```python
# Fork the repository
# Create your feature branch
git checkout -b feature/AmazingFeature

# Commit your changes
git commit -m 'Add some AmazingFeature'

# Push to the branch
git push origin feature/AmazingFeature

# Open a Pull Request
```
### Development Guidelines:
- Follow PEP 8 coding standards
- Add docstrings for new functions
- Include unit tests for new features
- Update documentation accordingly
- Ensure backward compatibility

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Samyar Zamani**
- **GitHub**: [@SamyarZamani](https://github.com/SamyarZamani)
- **LinkedIn**: [@Samyar Zamani](https://www.linkedin.com/in/samyar-zamani-71003537b/)

## 🙏 Acknowledgments

- **Iranian Real Estate Data Providers** - For comprehensive market data and access
- **Python Open-Source Community** - For powerful data science libraries and tools
- **Machine Learning Research Community** - For cutting-edge algorithms and methodologies
- **Contributors and Testers** - For valuable feedback, bug reports, and improvements
- **Real Estate Professionals** - For domain expertise, validation, and industry insights

---

**⭐ If you find this project useful, please give it a star!**

---

*Last updated: December 2023*  
*Compatible with Python 3.8+*  
*Active development status*




