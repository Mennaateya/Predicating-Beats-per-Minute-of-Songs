# 🎵 Song BPM Predictor – Kaggle Playground 2025 🎶

Welcome to the **BPM Prediction Project**!  
This repo is part of the **Kaggle Playground Series (S5E9)**, where the challenge is to predict the **Beats Per Minute (BPM)** of songs using their audio & metadata features.  

---

## 📌 Project Overview
- 🎯 **Goal**: Predict the continuous target `BeatsPerMinute` (BPM) of songs.  
- 📂 **Dataset**: Provided by Kaggle Playground (S5E9).  
- 🧩 **Features**: RhythmScore, AudioLoudness, VocalContent, AcousticQuality, InstrumentalScore, MoodScore, Energy, and more.  
- ⚡ **Approach**:
  - Data exploration & visualization  
  - Outlier detection & handling
  - Feature Engineering to select top 5 columns
  - Feature scaling with **RobustScaler, MinMaxScaler, StandardScaler**
  - Model training with **Linear, Tree-based, and Boosting regressors**  
  - Performance evaluation with **MAE, RMSE, R²**  

---

## 🚀 Models Tried
- Linear Regression  
- KNN Regressor  
- Decision Tree & Random Forest  
- Extra Trees, Bagging, AdaBoost  
- XGBoost, LightGBM, CatBoost  

📊 Final submission is based on the **best-performing model** after validation.  

---

## 📈 Results
All models were compared based on:
- **MAE** (Mean Absolute Error)  
- **RMSE** (Root Mean Squared Error)  
- **R² Score**  

The best model was saved and used for generating the Kaggle submission file ✅  

---

## 📂 Repository Structure
├── train.csv # Training dataset
├── test.csv # Test dataset
├── Files/ # Saved scalers & trained models
│ ├── *.pkl
├── Project.ipynb # Main notebook (EDA + Modeling)
├── app.py # (🚀 Streamlit app)
└── requirements

---

## 🛠️ Tech Stack
- **Python**  
- **Pandas, Numpy, Matplotlib, Seaborn, Plotly** (EDA & Visualization)  
- **Scikit-learn** (Preprocessing + ML Models)  
- **XGBoost, LightGBM, CatBoost** (Boosting models)  
- **Pickle** (Model saving/loading)  

---

## 🔮 Next Step
This is just the beginning! 🚀  
For future improvements, we plan to:  
- 🏆 Experiment with advanced hyperparameter tuning  
- 🎧 Add more audio-related engineered features  
- 🤖 Try deep learning models for better accuracy  

Stay tuned for more updates! ✨ 

---

## 🤝 Contribution
Wanna collaborate? Fork this repo, add your magic touch, and send a PR!  

---

## 📜 License
This project is open-source under the MIT License.  

---
Made with ❤️ for the Kaggle Playground Series 2025.  

