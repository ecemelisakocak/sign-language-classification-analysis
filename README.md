# Sign Language Data Representation & Classification
A comparative analysis of dimensionality reduction techniques for sign language image classification. This project explores whether different data representation methods improve or hinder classification performance.

## Methods
* Raw image data
* Principal Component Analysis (PCA)
* Kernel PCA (kPCA)
* Isomap
* RBF Kernel Support Vector Machine (SVM)

## Dataset
The project uses the **Sign Language Detection Using Images** dataset from Kaggle. Images were preprocessed, resized, normalized, and converted into feature vectors for analysis.

## Results
PCA achieved **99.95% cross-validation accuracy**, while optimized kPCA reached **100%**. Isomap achieved approximately **99.08%**, demonstrating strong classification performance but substantially higher computational cost.

Overall, the results show that more sophisticated representations can improve visualization and classification, but the additional computational complexity does not always provide a meaningful advantage when the raw data is already highly separable.

## Tools
MATLAB · PCA · Kernel PCA · Isomap · SVM · Data Visualization
