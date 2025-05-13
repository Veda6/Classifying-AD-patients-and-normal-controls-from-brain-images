# Classifying-AD-patients-and-normal-controls-from-brain-images
Classifying Alzheimer's Disease from MRI scans using SVM and PCA
# Alzheimer's Disease Classification from MRI Scans

This project focuses on classifying Alzheimer's Disease (AD) patients vs. normal controls using structural MRI scans. The pipeline combines classic image preprocessing techniques with Support Vector Machines (SVM) and Principal Component Analysis (PCA).

## 🧠 Key Techniques Used
- Skull Stripping using FSL BET
- Tissue Segmentation (CSF, Grey Matter, White Matter)
- Image Registration using NiftyReg
- ROI-based Volume Analysis
- Classification using Support Vector Machines
- Dimensionality Reduction using PCA

## 📂 Files Included
- `alzheimers-classification.ipynb`: Colab notebook with full pipeline implementation
- `annotated-Project1_5622.docx.pdf`: Full academic report with figures and explanations

## 📊 Sample Results
- SVM achieved **100% classification accuracy** on test data
- PCA scatter plot clearly separates AD and NC classes
- All preprocessing steps (skull stripping, segmentation, registration) visualized

## 🛠 Tools and Libraries
- Python (pandas, scikit-learn, numpy)
- FSL (BET, FAST, FSLstats)
- NiftyReg for image registration
- Colab and Jupyter for experimentation

## 📈 Output Visuals
(Include screenshots in `/images` folder if available)

## ⚠️ Disclaimer
This project was completed as part of a postgraduate lab assignment at the University of Sydney. It reflects academic exploration and is not intended for clinical use.

