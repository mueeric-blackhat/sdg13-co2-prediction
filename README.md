# 🌍 SDG 13: Predicting CO₂ Emissions Using Machine Learning

This project applies supervised machine learning to forecast national CO₂ emissions based on GDP and population data.  
It supports **United Nations Sustainable Development Goal 13 (Climate Action)** by helping visualize and anticipate future emission trends.

---

## 📌 Problem Statement

Carbon dioxide (CO₂) emissions significantly contribute to climate change.  
By predicting emissions using economic indicators, we can support proactive climate action, inform policy, and encourage sustainable practices.

---

## 🧠 Machine Learning Approach

- **Type**: Supervised Learning (Regression)
- **Algorithm**: Linear Regression
- **Features**: GDP, Population
- **Target Variable**: CO₂ Emissions (in megatons)

---

## 📊 Dataset

- Format: `CSV` file
- Columns: `Country`, `Year`, `GDP`, `Population`, `CO2_Emissions`
- Source: Simulated for educational use (inspired by World Bank Open Data)

---

## 🧪 Tools & Libraries

- Python
- Jupyter Notebook
- pandas, matplotlib, scikit-learn
- Optional: seaborn (for future improvements)

---

## 🚀 How to Run

1. Clone or download the repository
2. Open `SDG13_CO2_Prediction.ipynb` in Jupyter Notebook
3. Run the cells step-by-step or select **Kernel → Restart & Run All**
4. View evaluation metrics and graph

---

## 📈 Results

- **R² Score**: (Varies per run) ~0.84
- **Mean Absolute Error**: ~270,000 Mt
- **Visualization**: Scatter plot comparing predicted and actual CO₂ emissions

---

## 🔍 Ethical Considerations

- **Bias**: Data underrepresentation can skew accuracy, especially in developing countries.
- **Fairness**: Ensuring diversity in data helps make results equitable.
- **Sustainability**: Predictions can help policymakers plan for emissions reduction.
- **Transparency**: Linear regression is explainable and appropriate for early analysis.
- **Next Steps**:
  - Use more features like renewable energy usage
  - Try advanced models like Random Forest or XGBoost

---

## 📂 Project Files

```plaintext
├── SDG13_CO2_Prediction.ipynb         # Main notebook with code & output
├── co2_data.csv                       # Dataset
├── SDG13_CO2_1Page_Report.pdf         # Summary report
├── SDG13_CO2_Prediction_Presentation.pdf   # Slides in PDF
└── README.md                          # This file
