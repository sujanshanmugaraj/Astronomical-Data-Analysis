# Astronomical-Data-Analysis

This study presents a comprehensive machine learning approach for the automated classification of celestial objects, specifically distinguishing between stars and galaxies using digital image data. The dataset comprises 3,986 grayscale astronomical images, with an unbalanced distribution of 3,044 stars and 942 galaxies, representing a significant class imbalance ratio of approximately 3:1.
The methodology involves a sophisticated image processing pipeline where each image is standardized to 64x64 pixels and normalized to pixel values between 0 and 1. The preprocessing steps include grayscale conversion, size normalization, and pixel-value normalization to ensure consistent input features for the machine learning models. The implementation utilizes various Python libraries including NumPy for numerical operations, OpenCV for image processing, scikit-learn for machine learning operations, and scikit-image for advanced feature extraction.

The analysis framework incorporates multiple computational approaches:
1.	Data loading and organization using a custom-built function that maintains class labels
2.	Exploratory data analysis to understand class distribution and image characteristics
3.	Principal Component Analysis (PCA) for dimensionality reduction while preserving data variance
4.	Implementation of various feature extraction techniques including HOG (Histogram of Oriented Gradients) and LBP (Local Binary Patterns)
5.	Preparation for multiple classification algorithms including Support Vector Machines (SVM), K-Nearest Neighbors (KNN), Random Forests and XGBoost

The significant class imbalance presents a notable challenge that necessitates careful consideration in model development and evaluation. This research aims to contribute to the field of astronomical object classification by developing robust, automated classification methods that can assist in large-scale astronomical surveys and data processing.
The initial results suggest that the dimensional complexity of the data can be effectively reduced while maintaining significant variance, as indicated by the PCA analysis. This study lays the groundwork for future improvements in automated celestial object classification systems and demonstrates the potential of machine learning applications in astronomical research.

