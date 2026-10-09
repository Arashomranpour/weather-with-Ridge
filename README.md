<div align="center">

# 🌡️ Weather Forecasting with Ridge Regression

**Predict temperature from historical daily weather records using a regularised linear model.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`i.ipynb` works on the daily weather file `3393460.csv` (precipitation `PRCP`, maximum `TMAX` and minimum `TMIN` temperature):

1. 🧹 **Cleaning** - missing precipitation is set to 0 and missing temperatures are forward-filled.
2. 📊 **EDA** - temperature and precipitation plots, yearly precipitation totals.
3. 🧠 **Modelling** - a scikit-learn **Ridge regression**.
4. 💾 The trained model is saved as `weather.pkl`.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/weather-with-Ridge.git
cd weather-with-Ridge
pip install pandas numpy scikit-learn matplotlib jupyter
jupyter notebook i.ipynb
```

## 📁 Project Structure

```
.
├── i.ipynb        # Cleaning, EDA, Ridge model
├── 3393460.csv    # Daily weather data
└── weather.pkl    # Saved model
```

## 🛠️ Tech Stack

`scikit-learn` · `pandas` · `NumPy` · `Matplotlib`
