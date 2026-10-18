
# Project 3: Unsupervised Learning (Customer Segmentation with PCA & K-Means)

Unsupervised machine learning project that groups retail customers by purchasing behaviour and turns the groups into **business personas**. Built as part of my **Data Science Internship (Project 3)**.

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![scikit-learn](https://img.shields.io/badge/scikit--learn-ML-F7931E?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data-150458?logo=pandas)

---

##  What I Did
- **Prepared the data:** cleaned 1,200 retail orders, one-hot encoded the categorical columns and aggregated to **1,189 customers × 30 features**
- **Reduced dimensions:** used **PCA** to compress 30 features into **2 components** (Spending and Channel/Product preference)
- **Chose the number of clusters:** used the **Elbow Method** and **Silhouette Score** to show that **k = 3** is optimal (silhouette = 0.365)
- **Segmented customers:** applied **K-Means** and profiled each cluster
- **Translated results for the business:** created 3 customer personas with marketing recommendations

---

## Key Results

| Persona | Customers | Avg Spend | Revenue Share | Strategy |
|---|---|---|---|---|
|  Premium Bulk Buyers | 403 | $1,966 | **63%** | VIP loyalty program, volume discounts |
| Referral-Driven Tech Shoppers | 413 | $606 | 20% | Referral rewards, accessory bundles |
| ️ Budget Social-Media Shoppers | 373 | $597 | 18% | Instagram promos, easier payments |

💡 **Key insight:** about one-third of customers generate **63% of total revenue**.

---

## Tech Stack
**Python** · **Pandas** · **NumPy** · **Scikit-learn** · **Matplotlib** · **Seaborn** · **Jupyter**

## Files
- `Project3_Customer_Segmentation.ipynb`: main notebook (PCA, Elbow + Silhouette, K-Means, Personas)
- `Dataset for Data Analytics - Sheet1.csv`: dataset
- `Project3_Customer_Segmentation.html`: exported notebook (opens in any browser)
- `requirements.txt`: Python libraries

---



## How to run in VS Code
1. Install the **Python** and **Jupyter** extensions in VS Code.
2. Open this folder: File > Open Folder.
3. In the terminal, run: `pip install -r requirements.txt`
4. Open `Project3_Customer_Segmentation.ipynb`, select your Python kernel (top right), then click **Run All**.

Keep the CSV in the same folder as the notebook.

## ▶️ Run It

```bash
pip install -r requirements.txt
jupyter notebook Project3_Customer_Segmentation.ipynb
```

---

## Author
**Laiba Aslam**


**BS Information Technology (BSIT)**

**Studentat at
University of Sindh, Jamshoro**


Interests: Data Science, Data Analytics, and Machine Learning.
