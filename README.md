# Country Schools Data Analysis — Lab 2

## Project Overview

This project applies basic data preprocessing and machine learning techniques to the Country Schools dataset. The main objective is to identify unusual school installation patterns and group counties with similar characteristics.

## Objectives

- Perform basic data preprocessing.
- Detect anomalies using Isolation Forest.
- Perform cluster analysis using K-Means.
- Visualize and interpret the results.

## Technologies Used

- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Kaggle

## Methodology

**1. Data Preprocessing:** Removed missing records and the national TOTAL row, converted installation percentages into numerical values, selected relevant features, and standardized the data.

**2. Anomaly Detection:** Applied Isolation Forest to identify counties with unusual installation characteristics.

**3. Cluster Analysis:** Applied K-Means clustering and evaluated the number of clusters using the Elbow Method and Silhouette Score.

## Results

- **47 counties** were analyzed after preprocessing.
- **5 anomalous counties** were identified using Isolation Forest.
- K-Means grouped the counties into **3 clusters**.
- The clusters revealed differences in school populations, installation rates, and installed devices.

## Conclusion

This project demonstrates how machine learning can be used to identify unusual observations and discover meaningful patterns in educational data through anomaly detection and clustering.
