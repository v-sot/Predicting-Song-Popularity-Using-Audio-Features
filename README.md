# Predicting Song Popularity Using Audio Features 🎵

This project explores the use of machine learning techniques to predict the popularity of songs based on their audio characteristics.

It was developed as part of my dissertation thesis and focuses on understanding how features such as tempo, energy, danceability, and loudness influence a song’s success.

---

## 📖 Overview

The music industry increasingly relies on data-driven insights to understand audience preferences.  

In this project, I analyze a dataset of songs with extracted audio features and build predictive models to estimate **song popularity**.

---

## 🎯 Objective

To build a model that predicts a song’s popularity score using audio features and to identify which features contribute most to a song’s success.

---

## 📂 Dataset

The dataset contains song-level data, including:

- Audio features:
  - Danceability  
  - Energy  
  - Loudness  
  - Tempo  
  - Acousticness  
  - Valence  
  - Speechiness  
- Additional attributes:
  - Duration  
  - Popularity score (target variable)

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Handling missing values  
- Feature scaling / normalization  
- Exploratory Data Analysis (EDA)  

### 2. Feature Analysis
- Correlation analysis  
- Identification of important predictors  
- Visualization of relationships  

### 3. Model Development
- Training machine learning models (e.g., Linear Regression, etc.)  
- Model tuning and evaluation  

### 4. Model Evaluation
- Performance metrics such as:
  - R² score  
  - Mean Squared Error (MSE)  

---

## 📊 Key Insights

- Certain audio features (e.g., energy, danceability) show strong relationships with popularity  
- Popularity is influenced by a combination of multiple features rather than a single factor  
- Predicting popularity is inherently noisy due to external factors (marketing, trends, artist popularity)  

---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

## 📁 Repository Structure

```
├── code.ipynb
├── df_final.csv 
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository  
2. Open the notebook:
   ```
   code.ipynb
   ```
3. Ensure dataset path is correct  
4. Run all cells  

---

## 💡 Why This Project Matters

This project demonstrates:

- Application of machine learning to a real-world problem  
- Feature engineering and data analysis skills  
- Ability to interpret model results and extract insights  

---

## 📌 Notes

- This project was developed as part of an academic dissertation  
- Results are for analytical purposes and may not capture all real-world factors affecting song popularity  

---

## 👤 Author

Vasileios Sotiriadis
