# QSAR Data Curation using ChEMBL – Assignment 2

**Student:** Aysha Mehrin  
**Course:** AI and Drug Discovery – 2026  
**Task:** Assignment 2 – QSAR Data Curation  

---

## 📄 Overview

This repository contains the complete workflow for **curating bioactivity data** from ChEMBL, focusing on the target **Acetylcholinesterase (CHEMBL220)**. The curated dataset is suitable for downstream **QSAR modeling**.  

The notebook retrieves IC50 bioactivity values, cleans and filters the data, and saves the curated dataset in a ready-to-use CSV file.

---

## 🗂 Repository Contents

| File Name | Description |
|-----------|-------------|
| `Assignment_2_QSAR_data_curation.ipynb` | Complete Jupyter Notebook for Assignment 2, with all steps from target search to curated dataset export. |
| `curated_bioactivity_data.csv` | Final curated IC50 dataset for CHEMBL220 (7523 rows, nM units, exact measurements). |
| `Aysha_Mehrin_Task_2.pdf` | One-page summary report of the assignment. |

---

## 🧪 Notebook Workflow

1. **Install Required Libraries**  
   `chembl_webresource_client`, `pandas`, `numpy`  

2. **Import Libraries**  
   Load Python packages for data retrieval and manipulation.  

3. **Target Search**  
   Search for *acetylcholinesterase* in ChEMBL.  

4. **Select Target**  
   Select CHEMBL220 (acetylcholinesterase).  

5. **Retrieve Bioactivity Data**  
   Get all IC50 measurements for CHEMBL220.  

6. **Select Relevant Columns**  
   Keep only `molecule_chembl_id`, `canonical_smiles`, `standard_value`, `standard_units`, `standard_relation`.  

7. **Data Cleaning**  
   - Remove missing values  
   - Keep only exact measurements (`=`)  
   - Convert IC50 to numeric  

8. **Standardize Units**  
   Filter to keep only **nM** values.  

9. **Save Curated Dataset**  
   Export to `curated_bioactivity_data.csv`.  

10. **Final Check**  
    Confirm dataset summary and ensure data is ready for QSAR modeling.

---

## ✅ Notes

- Total IC50 records after curation: **7523 rows**  
- All IC50 values are in **nM** units  
- All measurements are **exact (`=`)**  

---

## 📤 Submission Instructions

1. Upload repository to GitHub:  
   **Repo name must be exactly:** `AI_and_Drug_Discovery_Course_2026`  

2. Include the following files:  
   - `Assignment_2_QSAR_data_curation.ipynb`  
   - `curated_bioactivity_data.csv`  
   - `Aysha_Mehrin_Task_2.pdf`  

3. Fill the Google Form with the **same email as Assignment 1**, paste GitHub repo link, and upload the summary PDF.  

---

*Prepared by Aysha Mehrin – 2026*
