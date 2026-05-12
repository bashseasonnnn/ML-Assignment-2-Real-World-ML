# COMS3007A – Assignment 2: Applied Machine Learning

## 🧠 Project Overview


The goal is to build a robust classification pipeline that predicts physical actions from multivariate, time-series sensor data collected from a wearable device.



The final evaluation metric is **Macro-F1 score**, evaluated via a Kaggle competition (private leaderboard determines final grade).

---

## 👥 Group Members

- Simphiwe M Tech — Student Number: 2697002  
- Tshepo Mnogemezulu — Student Number: 2740751  
- Bohlale Mabonga - Student Number : 2693726

---

## 📊 Problem Description

We are given sensor data in a long-format time-series structure:

- Each `Sample_ID` represents one physical action instance
- Each sample contains:
  - 100 time steps
  - 14 sensor signals
- Task: classify each sample into one of **6 action classes**

### Key Challenges:
- Missing sensor data (dropouts)
- Noisy and correlated signals
- Strong temporal dependencies
- High risk of overfitting to leaderboard

---

## 📁 Project Structure
