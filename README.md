# 🧪 Drug Discovery Practical — Virtual Screening & AI Analysis

This repository contains **general code and workflows** I developed during a practical course on *Drug Discovery*.  
The focus of the project is on **structure- and machine learning-based virtual screening for novel Alzheimer’s disease targets (e.g., STK33 kinase)**, integrating cheminformatics, docking, and ML pipelines.

> ⚠️ Note: All scripts are **educational and demonstrative**. They illustrate typical workflows used in drug discovery, not production-ready pipelines.

---

## 📚 Workflow Overview

- **Data Preparation & Molecular Representation**  
  Handling chemical datasets, preprocessing, and fingerprint generation (e.g., ECFP4).

- **Ligand-Based Drug Discovery (LBDD)**  
  Molecular similarity search and filtering based on fingerprints.

- **Structure-Based Drug Discovery (SBDD)**  
  Protein structure modeling, active site prediction, and docking with AutoDock Vina.

- **Machine Learning Integration**  
  Training models (Random Forest) to predict binding affinity and applying them to large libraries.

- **Blood–Brain Barrier Permeability (BBBP) Prediction**  
  Filtering candidate molecules to identify CNS-permeable compounds.

- **Hit Visualization & Analysis**  
  PyMOL visualization of docking poses, hydrogen bond interactions, and pocket analysis.

---

## 🧬 Main Project Example

**Topic:** *Structure- and Machine Learning-Based Virtual Screening for STK33 Inhibition in Alzheimer’s Disease*

- **Objective:** Identify novel candidate compounds for Alzheimer’s treatment by targeting **STK33 kinase**, combining docking (SBDD), ligand filtering, and ML-based affinity prediction with BBB permeability evaluation.  
- **Results:**  
  - Docking with ~50,000 compounds identified high-affinity binders (top hit: -11.0 kcal/mol).  
  - ML + BBBP filtering yielded **50 promising CNS-permeable candidates**.  
  - PyMOL visualizations confirmed hydrogen bonds & hydrophobic interactions with STK33 binding pocket.  
  - Demonstrated **dual-optimization workflow** (affinity + drug-likeness) as critical in CNS drug design.

---

## 🛠️ Tools & Technologies

- **Cheminformatics:** RDKit, PubChem, Enamine libraries  
- **Docking:** AutoDock Vina, P2Rank, SWISS-MODEL  
- **Data Science:** Python, Pandas, Scikit-learn, t-SNE visualization  
- **ML Models:** Random Forest regression with ECFP4 fingerprints  
- **Visualization:** PyMOL, Matplotlib, Seaborn  
- **Other:** Anaconda, Jupyter/Colab  

---

## 📌 Disclaimer
This repository is for **educational and research demonstration purposes only**.  
The codes are simplified to illustrate the **drug discovery workflow** and may not represent production-ready pipelines.
