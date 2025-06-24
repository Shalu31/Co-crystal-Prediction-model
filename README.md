# 💊 Co-crystal Prediction Model for BCS Class II Drugs

This project aims to predict the likelihood of co-crystal formation for poorly soluble drugs classified under BCS (Biopharmaceutics Classification System) Class II, using molecular descriptors and machine learning models.

---

## 📁 Table of Contents

* [Project Overview](#project-overview)
* [Objective](#objective)
* [Technologies Used](#technologies-used)
* [Dataset](#dataset)
* [Approach](#approach)
* [Model Evaluation](#model-evaluation)
* [Future Work](#future-work)
* [How to Use](#how-to-use)


---

## 🔬 Project Overview

BCS Class II drugs have high permeability but low solubility, making them ideal candidates for co-crystal engineering to enhance their bioavailability. This model uses molecular descriptors to predict the formation of co-crystals between an Active Pharmaceutical Ingredient (API) and co-formers.

---

## 🎯 Objective

* Predict whether a given API–co-former pair can form a stable co-crystal.
* Use cheminformatics and machine learning techniques to assist early-stage drug formulation efforts.

---

## 🧰 Technologies Used

* Python
* RDKit (molecular descriptor generation)
* Scikit-learn (machine learning)
* Pandas, NumPy (data handling)
* Matplotlib, Seaborn (visualization)

---

## 📊 Dataset

* API–co-former pairs with binary labels: `1` (successful co-crystal), `0` (no co-crystal).
* Descriptors used: MACCS keys, molecular weight, logP, number of H-bond donors/acceptors, etc.
* Data collected from **Cambridge Structural Database (CSD)** and related literature.

---

## 🔁 Approach

1. **Descriptor Extraction** using RDKit
2. **Data Preprocessing** – cleaning, feature scaling
3. **Model Training** – Logistic Regression, Random Forest, XGBoost
4. **Evaluation** – Accuracy, Precision, Recall, ROC-AUC
5. **Visualization** – Feature importance, correlation heatmaps

---

## 🚀 Future Work

* Explore deep learning (Graph Neural Networks) for improved accuracy.
* Integrate physicochemical interaction rules (e.g., hydrogen bonding networks).
* Build a user-friendly web app for co-crystal screening.

---

## ▶️ How to Use

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/co-crystal-prediction.git
   cd co-crystal-prediction
   ```
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook to train the model and view results.

---




