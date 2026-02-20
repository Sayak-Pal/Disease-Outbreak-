# 🦠 Machine Learning-Based Disease Outbreak Prediction System 📈

A **Streamlit-powered** machine learning web app that predicts the likelihood/risk of **Diabetes 🩸**, **Heart Disease ❤️**, and **Parkinson’s 🧠** using health parameters.  
It handles class imbalance using **Tomek’s Link 🔗**, trains ML models, saves them as **`.sav` 💾** files, and serves predictions through an interactive UI.

---

## 📝 Abstract

Predicting disease outbreaks (or disease risk) is crucial for **early intervention 🚑** and **public health planning 🏥**.  
This project analyzes health datasets for **Diabetes**, **Heart Disease**, and **Parkinson’s Disease**, balances the data using **Tomek’s Link**, and trains machine learning models for accurate predictions ✅.  
The trained model is saved as a **`.sav` file 💾** and integrated into a **Streamlit web application 🌐**, making it easy for users to get real-time predictions.

---

## ❓ Problem Statement

Disease outbreaks pose major public health challenges. Traditional approaches often fail when datasets are **imbalanced ⚖️**, leading to biased predictions. This project leverages **machine learning 🤖** + **data balancing (Tomek’s Link 🔗)** to improve predictive performance and accessibility.

---

## 🎯 Objectives

- 🖥️ **Build an interactive web interface** for easy user input & prediction  
- 🤖 **Train robust ML models** using real-world health datasets  
- ⚖️ **Handle class imbalance** using Tomek’s Link for better accuracy  
- 💾 **Save trained models** as `.sav` files for smooth deployment  
- 🌍 **Make it accessible** via GitHub + Streamlit Cloud  
- 🩺 **Encourage early health monitoring** and proactive care  

---

## ✨ Key Features

- 🩸 Diabetes Prediction
- ❤️ Heart Disease Prediction
- 🧠 Parkinson’s Disease Prediction
- 🔗 Tomek’s Link balancing for improved model learning
- 💾 Model saved/loaded via `.sav`
- 🎛️ User-friendly Streamlit interface
- 🚀 Easy deployment (GitHub + Streamlit Cloud)

---

## 🧠 Methodology (High-Level)

1. 📥 **Data Collection & Cleaning**  
   - Missing values, duplicates, normalization/standardization  
2. ⚖️ **Class Balancing**  
   - Tomek’s Link 🔗 to improve class separation  
3. 🧬 **Feature Engineering**  
   - Select relevant features, scaling & encoding  
4. 🏋️‍♂️ **Model Training**  
   - Logistic Regression / Decision Trees / Random Forest / SVM (as applicable)  
5. ✅ **Evaluation**  
   - Accuracy, Precision, Recall, F1-score + Confusion Matrix  
6. 🌐 **Deployment**  
   - Streamlit UI + saved model `.sav`  

---

## 🧰 Tech Stack

- 🐍 **Python 3.x**
- 📊 **NumPy, Pandas**
- 🤖 **Scikit-learn**
- ⚖️ **imbalanced-learn (Tomek’s Link)**
- 📉 **Matplotlib, Seaborn** (optional visualizations)
- 💾 **Pickle / Joblib** for `.sav`
- 🌐 **Streamlit**
- 🧑‍💻 **Git + GitHub**
- ☁️ **Streamlit Cloud**

---

## 💻 Requirements

### 🧱 Hardware
- ⚡ CPU: Intel i5 / AMD Ryzen 5 or higher
- 🧠 RAM: 8GB minimum (16GB recommended)
- 💽 Storage: ~500MB free (more if datasets included)
- 🌍 Internet: required for deployment & hosted usage
- 🎮 GPU: optional (only for deep learning variants)

### 🧩 Software
- 🪟 Windows / 🐧 Linux / 🍎 macOS  
- 🐍 Python 3.x  
- 🧑‍💻 Git  

---

## 🚀 Getting Started (Local Setup)

### 1️⃣ Clone the repository
```bash
git clone https://github.com/Sayak-Pal/Disease-Outbreak-.git
cd Disease-Outbreak-
```

### 2️⃣ Create & activate a virtual environment (recommended)
```bash
python -m venv .venv
# Windows:
.venv\Scripts\activate
# macOS/Linux:
source .venv/bin/activate
```

### 3️⃣ Install dependencies
If you have a `requirements.txt`:
```bash
pip install -r requirements.txt
```

If not, install typical packages:
```bash
pip install streamlit numpy pandas scikit-learn imbalanced-learn matplotlib seaborn
```

### 4️⃣ Run the Streamlit app
> Replace `app.py` with your actual app filename (common: `app.py`, `streamlit_app.py`).

```bash
streamlit run app.py
```

---

## 💾 Model Artifacts

- Trained ML models are stored as **`.sav` 💾** files  
- The Streamlit app loads these artifacts and returns predictions instantly ⚡

---

## 🖼️ Results (UI Outputs)

The app displays results such as:
- 🩸 **Diabetic / Non-Diabetic**
- ❤️ **Having Heart Disease / No Heart Disease**
- 🧠 **Having Parkinson’s Disease / No Parkinson’s Disease**

(Add screenshots to the repo and link them here for a more attractive README 📸✨)

---

## ☁️ Deployment (Streamlit Cloud)

1. ⬆️ Push code to GitHub  
2. 🔗 Connect repo in Streamlit Cloud  
3. 📌 Select entry file (`app.py`)  
4. 🚀 Deploy & share the link  

---

## ⚠️ Limitations

- 📉 Accuracy depends on dataset quality and completeness  
- 🧪 Only 3 diseases are included currently  
- 🩺 Not a replacement for professional medical diagnosis  
- 🧍‍♂️ Potential bias if training data is not diverse  
- 🌐 Internet needed for online access  
- 🕵️ Limited explainability without additional tools  

---

## 🔮 Future Work

- ➕ Add more diseases & conditions  
- 🧠 Try advanced models (XGBoost, deep learning, ensembles)  
- 🔍 Add explainability (SHAP/LIME)  
- ⌚ Integrate wearable/device real-time data  
- 📱 Build a mobile application  
- 📊 Improve monitoring, logging & continuous updates  

---

## 📚 References

- Kavakiotis et al. (2017) — *ML & Data Mining in Diabetes Research*  
- Cheng et al. (2021) — *Early Heart Disease Prediction using ML*  
- Singh et al. (2020) — *Parkinson’s Prediction using ML Algorithms*  
- Pedregosa et al. (2011) — *Scikit-learn in Python*  
- Streamlit Docs (2024) — https://docs.streamlit.io/

---

## 🛑 Disclaimer

This project is for **educational and research purposes 🎓**.  
Predictions are model-based and should not be considered final medical diagnosis 🩺. Always consult healthcare professionals.

---

## 👤 Maintainer
GitHub: https://github.com/Sayak-Pal
