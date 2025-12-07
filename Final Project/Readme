## Project Overview

Severe burn injuries often lead to deeper complications that extend beyond the skin. Many patients develop **fractures**, **bone density loss**, or **osteomyelitis**, which cannot be detected from surface evaluation alone. Early identification is critical for surgical planning, long-term recovery, and clinical decision-making.

This project implements a **three-part analytical pipeline** (described in detail in the final report :contentReference[oaicite:1]{index=1}):

1. **Clinical Predictive Modeling**  
   - Random Forest Classifier (balanced)  
   - Targets: *has_fracture* and *has_osteomyelitis*  
   - Key predictors: burn severity index, bone damage score, hospital stay duration, antimicrobial material properties  

2. **Principal Component Analysis (PCA)**  
   - PC1: *Severity–Bone Damage Axis*  
   - PC2: *Treatment–Comorbidity Axis*  
   - Reveals clear structural clustering for fracture-positive patients  

3. **CNN + UMAP CT Imaging Analysis**  
   - 72 right-knee DICOM slices  
   - ResNet-50 used for 2048-dimensional feature extraction  
   - UMAP used for 2D embedding and anatomical clustering  
   - Distinct regions identified:
     - Distal tibia  
     - Knee joint  
     - Proximal tibia / lower femur  

---

##  Included Notebooks

### **1. Clinical_Modeling.ipynb** (refer to the other folder)
Implements:
- Data preprocessing  
- Class balancing  
- Random Forest modeling  
- ROC-AUC, PR-AUC, confusion matrices  
- Feature importance interpretation  

### **2. PCA_BurnCare.ipynb**
Explores:
- Standardization & PCA fitting  
- Component loadings  
- PC1 vs. PC2 visualization  
- Relationship between PCA embeddings and bone health outcomes  

### **3. UMAP_Bone_Images.ipynb**
Performs:
- DICOM preprocessing  
- ResNet-50 feature extraction  
- UMAP 2D projection  
- Cluster visualization and anatomical interpretation  

UMAP clusters described in the report (page 7) reveal **5–7 subclusters** driven by fine-grained cortical, trabecular, and cartilage features.

---

## Key Findings From the Final Report

Based on the full analysis (described in *MSBD566_FinalProject.pdf* :contentReference[oaicite:2]{index=2}):

- Burn severity, bone damage metrics, and hospital stay duration are the **strongest predictors** of internal bone complications.  
- Material properties (e.g., antimicrobial coating, weight, stretch limit) contribute meaningfully to prediction.  
- PCA provides interpretable structure connecting severity and bone outcomes.  
- CNN-UMAP reveals anatomical clusters **without labels**, demonstrating potential for unsupervised injury detection.  

---

## Limitations

- Significant class imbalance (osteomyelitis = 9.4% positive).  
- Limited number of imaging cases.  
- Variation in CT imaging quality.  
- No longitudinal imaging to track progression.  

---

## Citation  
If referencing this project or its contents, please cite the final project report and author:

> Davis, L. (2025). *Integrating Clinical Predictive Modeling and Imaging-Based Analysis to Identify Bone Health Complications in Burn Patients.* MSBD566 Final Project. :contentReference[oaicite:3]{index=3}

---

##  Author  
**LaPorchia Davis**  
Biomedical Data Science – Meharry SACS   

---

## Questions or Improvements?
Feel free to open an issue or request enhancements to the notebooks or documentation. Contact the research LaPorchia Davis for more information
