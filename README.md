
# 🏠 House Price Prediction & Market Segmentation in Kuala Lumpur, Malaysia


<img width="1032" height="532" alt="image" src="https://github.com/user-attachments/assets/1a457e72-1601-405a-875a-25358586885a" />




This project applies **machine learning** to the Kuala Lumpur housing market, focusing on two main goals:

1. **Predicting house prices** using supervised learning.
2. **Segmenting the property market** into meaningful categories (e.g., affordable vs. luxury) using unsupervised learning.

This was developed as part of a group academic project to demonstrate how data science can be applied to real-world real estate challenges.

🔗 **GitHub by:** [@mlkinteh2](https://github.com/mlkinteh2)

---

## 📌 Objectives

* Predict housing prices with machine learning models.
* Segment properties into **affordable** and **luxury** markets using clustering.
* Derive insights and trends from the Kuala Lumpur real estate dataset.

---

## 📂 Project Workflow

### ✅ Data Cleaning & Preprocessing

* Handled missing values and inconsistent formats.
* Removed outliers.
* Encoded categorical variables (one-hot & frequency encoding).
* Normalized numerical features.

### ✅ Modeling

* **Supervised Learning:** Linear Regression, Random Forest, and more.
* **Unsupervised Learning:** K-Means Clustering for market segmentation.

### ✅ Evaluation & Insights

* Achieved strong predictive performance on house prices.
* Identified two distinct market segments: **affordable** vs. **luxury**.
* Visualized price distributions, cluster characteristics, and feature importance.

---

## 📊 Tools & Libraries

* **Programming:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Flask

---

## 🖼️ Screenshots

### Web Application – Flask UI

#### Home Page (Form Input)

<img width="1170" height="861" alt="image" src="https://github.com/user-attachments/assets/3ec19082-690c-4e19-99d9-b147c011a9d9" />


#### Prediction Result (Example)



<img width="1126" height="620" alt="image" src="https://github.com/user-attachments/assets/7928ce9c-0468-427a-b820-397fe8a9b7b5" />


---

## 🗂 Repository Structure

| File Name                                         | Description                                                                 |
| ------------------------------------------------- | --------------------------------------------------------------------------- |
| `House price prediction and market segment.ipynb` | Main notebook with data preprocessing, modeling, and results visualization. |
| `run.py`                                          | Flask app script to serve predictions and segmentation.                     |
| `templates/index.html`                            | Frontend HTML form for input.                                               |
| `static/style.css`                                | CSS styles for the web app.                                                 |

---

## ⚙️ How to Run Locally

Follow these steps to set up and run the project on your local machine:

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/mlkinteh2/house-price-kl.git
cd house-price-kl
```

### 2️⃣ Create Virtual Environment (optional but recommended)

```bash
python -m venv venv
source venv/bin/activate   # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Run Jupyter Notebook (optional for analysis)

```bash
jupyter notebook
```

### 5️⃣ Run the Flask App

```bash
python run.py
```

### 6️⃣ Open in Browser

Go to:

```
http://127.0.0.1:5000/
```

You’ll see the web interface where you can input house details and get predictions 🚀.

---


## 👨‍💻 Author

**Modou Lamin Kinteh**
GitHub: [mlkinteh2](https://github.com/mlkinteh2)


