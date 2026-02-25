## 📌 Overview

This repository contains the work for **Assignment 3**, which focuses on performing **exploratory data analysis (EDA)** and calculating **molecular descriptors and fingerprints** using curated ChEMBL bioactivity data from Assignment 2. The generated features are intended for downstream **QSAR and machine learning–based drug discovery analysis**.

---

## 🧪 Dataset Description

* **Source:** Curated ChEMBL bioactivity dataset (Assignment 2)
* **Number of molecules:** **7,522**
* **Data includes:**

  * ChEMBL compound IDs
  * Canonical SMILES strings
  * pIC50 values
  * Bioactivity class labels (active / inactive)

---

## 🧩 Tasks Completed

### 🔹 Task 1: Exploratory Data Analysis (EDA)

* Computed basic statistics (mean, min, max, standard deviation) for pIC50
* Visualized pIC50 distribution using histogram and density plots
* Created bar plots to show bioactivity class distribution
* Analyzed relationships between physicochemical descriptors and pIC50

---

### 🔹 Task 2: Molecular Descriptor Calculation

* Calculated **Lipinski descriptors** using RDKit:

  * Molecular Weight (MolWt)
  * LogP
  * Hydrogen Bond Donors
  * Hydrogen Bond Acceptors
* Saved descriptors as a CSV file for reproducibility

---

### 🔹 Task 3: Fingerprint Generation

* Generated **MACCS structural fingerprints** using RDKit
* Each molecule represented by **166 fingerprint bits**
* Fingerprints exported as a CSV file for QSAR modeling

---

## 🛠 Tools and Technologies

* **Google Colab**
* **Python**
* **RDKit**
* **pandas, NumPy**
* **matplotlib, seaborn**

---

## 📂 Repository Structure

```
AI_and_Drug_Discovery_Course_2026/
│
├── Assignment_1_Target_Selection.ipynb
│
├── Assignment_2_QSAR_data_curation.ipynb
│   └── curated_bioactivity_data.csv
│
├── Assignment_3_EDA_Descriptors.ipynb
│   ├── lipinski_descriptors.csv
│   └── maccs_fingerprints.csv
│
├── Aysha_Mehrin_Task_3.pdf
│
└── README.md
```

---

## 📄 Results Summary

* Key EDA insights and visualizations are included in the notebook
* Lipinski descriptors and MACCS fingerprints were successfully generated
* A one-page summary report (`Aysha_Mehrin_Task_3.pdf`) is included

