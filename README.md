# 🌾 Yield Prediction & Analysis using AI

This project was developed as part of the **Green Skilling and AI Bootcamp** organized by Edunet Foundation at **Symbiosis Institute of Technology**. The objective is to predict agricultural crop yields using machine learning techniques, helping promote sustainable and data-driven farming practices.

---

## 📌 Problem Statement

With the increasing challenges posed by climate change and variable environmental conditions, accurate prediction of crop yields is essential for effective agricultural planning. This project leverages machine learning to model and predict crop yields based on historical agricultural data, rainfall, and usage of fertilizers and pesticides.

---

## 📂 Project Structure

```

Yield-Prediction-&-Analysis/
│
├── Yield-Prediction-&-Analysis.ipynb      # Jupyter notebook with full code
├── crop\_yield.csv                         # Dataset used for training the model
├── Yield-Prediction-&-Analysis.pdf        # Final project report
└── README.md                              # Project documentation

```

---

## 📊 Dataset Description

- **Source:** Kaggle - Crop Yield Prediction Dataset  
- **Records:** 9022  
- **Features (10 total):**
  - `Crop`
  - `Crop_Year`
  - `Season`
  - `State`
  - `Area` (in hectares)
  - `Production` (in metric tons)
  - `Annual_Rainfall` (in mm)
  - `Fertilizer` (in kg)
  - `Pesticide` (in kg)
  - `Yield` (calculated = Production / Area)

---

## 🧠 Methodology

- **Data Preprocessing:**
  - Missing value treatment
  - One-hot encoding for categorical variables
  - Feature scaling using `StandardScaler`
  - Normalization of the target variable `Yield`

- **Model Used:** `Linear Regression`
- **Train-Test Split:** 80-20
- **Evaluation Metrics:**
  - R² Score: **0.8541**
  - RMSE: **0.0191**

---

## 📈 Visualizations

- Histograms for Area, Production, Rainfall, Fertilizer, and Pesticide usage
- Fit line graph comparing actual vs predicted yields

---

## 🔍 Key Insights

- Features like fertilizer and rainfall show significant correlation with crop yield.
- Linear Regression performed well, but can be further improved with advanced models.

---

## 🚀 Future Enhancements

- Implement advanced models like:
  - Random Forest
  - Gradient Boosting
  - Deep Learning (ANN, RNN)
- Integrate real-time data via IoT for dynamic predictions
- Build a Streamlit or Flask web app for deployment

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- Git & GitHub

---

## 📜 License

This project is part of an educational initiative and is open for learning and research purposes.

---

## 📎 References

- [Kaggle - Crop Yield Prediction Dataset](https://www.kaggle.com/datasets)  
- [Scikit-learn Documentation](https://scikit-learn.org/)
```

---
