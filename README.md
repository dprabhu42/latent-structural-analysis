
# Statistical Learning Approaches for Breast Cancer 

This project explores the statistical structure of breast cancer biomarker data using clustering, Principal Component Analysis (PCA), and Singular Value Decomposition (SVD). The analysis investigates latent biological structure, dimensionality reduction, and biomarker relationships within high-dimensional biomedical data using statistical learning techniques.

Using the Breast Cancer Wisconsin (Diagnostic) Dataset from the UCI Machine Learning Repository, this project examines how correlated tumor biomarkers can be compressed into lower-dimensional representations while preserving meaningful biological variation. Exploratory analysis, clustering, PCA visualizations, and matrix decomposition methods were used to identify dominant underlying patterns across tumor samples.

## Methods Used
- Exploratory Data Analysis (EDA)
- Correlation Analysis
- Data Standardization
- K-Means Clustering
- Principal Component Analysis (PCA)
- Singular Value Decomposition (SVD)
- Dimensionality Reduction
- Statistical Learning

## Key Findings
- Strong correlations between biomarkers suggested overlapping biological information and redundancy within the dataset.
- PCA demonstrated that much of the dataset’s variation could be preserved using a smaller number of principal components.
- PCA visualizations revealed meaningful latent structure and noticeable separation between tumor diagnosis groups.
- SVD identified dominant underlying patterns within the biomarker matrix, supporting dimensionality reduction approaches for complex biomedical datasets.

## Dataset
This project uses the Breast Cancer Wisconsin (Diagnostic) Dataset from the UCI Machine Learning Repository, accessed through scikit-learn. The dataset contains numerical biomarker features computed from digitized images of breast mass cell nuclei obtained through fine needle aspiration (FNA).

## Technical Skills Demonstrated
- Python
- pandas
- NumPy
- scikit-learn
- plotnine
- Statistical Learning
- Biomedical Data Analysis
- Unsupervised Learning
- Matrix Decomposition
- Data Visualization

## Future Directions
Future work could explore supervised classification models, larger genomic-scale biomarker datasets, and advanced machine learning approaches for biomedical pattern detection and healthcare analytics.
