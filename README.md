# 🎵 Song Popularity Analysis and Prediction

This project explores and models the factors influencing the popularity of songs using audio features extracted from the Spotify API. The analysis is performed on a dataset of over 18,000 songs and includes exploratory data analysis (EDA), feature correlation, and predictive modeling.

---

## 📊 Project Objectives

- Perform EDA to understand patterns in song characteristics
- Visualize relationships between features and song popularity
- Identify and eliminate multicollinear features
- Build regression models to predict song popularity based on audio features

---

## 🗂 Dataset Overview

- 📄 File: `song_data.csv.xlsx`  
- 🔢 Records: 18,835 songs  
- 📈 Features:
  - `acousticness`, `danceability`, `energy`, `instrumentalness`, `tempo`, `valence`, etc.
  - Target: `song_popularity`

---

## 🛠 Tools & Libraries

- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📌 Key Steps

1. **Data Cleaning**  
   - Checked for nulls, duplicates  
   - Standardized feature formats

2. **Exploratory Data Analysis (EDA)**  
   - Distribution plots of audio features  
   - Correlation heatmap and pairwise analysis

3. **Feature Selection**  
   - Removed multicollinear features (r > 0.6)  
   - Visualized key contributors to popularity

4. **Modeling**  
   - Trained regression models (Random Forest, Linear Regression)  
   - Evaluated with RMSE and R² scores

---

## 📈 Results

- Identified that **energy**, **danceability**, and **valence** significantly affect song popularity
- Built models that could reasonably predict popularity scores
- Visualized key audio trends across different song types

---
## 📎 How to Run

    ```bash

    # Clone the repository
      git clone https://github.com/Sohan-hub11/Song-Popularity-EDA.git

    # Open the notebook
      cd Song-Popularity-EDA
      jupyter notebook song_popularity_analysis.ipynb

---

## 👨‍💻 Author

Made with ❤️ by [Sohan Samanta](https://github.com/Sohan-hub11)

---

⭐ If you found this helpful, give it a **star** and consider contributing!

