<p align="center">
  <a href="https://skills.network" target="_blank">
    <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
  </a>
</p>

# 🏥 **Practice Project: Insurance Cost Analysis**

**Estimated time needed:** 75 minutes

In this project, you will perform data analytics operations on an **insurance dataset** using Python and Scikit-learn. The objective is to build and refine regression models to predict **insurance charges** based on several parameters.

---

## 📊 Dataset Description

| Parameter | Description | Type |
|------------|--------------|------|
| `age` | Age in years | integer |
| `gender` | Male or Female | integer (1 or 2) |
| `bmi` | Body Mass Index | float |
| `no_of_children` | Number of children | integer |
| `smoker` | Whether smoker or not | integer (0 or 1) |
| `region` | US Region - NW, NE, SW, SE | integer (1,2,3,4) |
| `charges` | Annual Insurance charges (USD) | float |

---

## 🎯 Objectives

You will:
- Load the data into a `pandas` dataframe.
- Clean and preprocess the data.
- Perform **Exploratory Data Analysis (EDA)** to find key factors affecting insurance charges.
- Develop:
  - **Simple Linear Regression** models.
  - **Multiple Linear Regression** models.
- Use **Ridge Regression** for model refinement and to handle overfitting.

---

## ⚙️ Setup

### Required Libraries
Install and import the following libraries:

```python
import piplite
await piplite.install('seaborn')
