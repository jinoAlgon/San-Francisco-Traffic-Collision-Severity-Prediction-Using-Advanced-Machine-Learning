# San Francisco Traffic Collision Severity Prediction

## Overview
This project aims to predict the severity of traffic collisions in San Francisco using machine learning techniques, with a focus on aiding the SFPD in reducing traffic accidents and fatalities. It leverages a comprehensive dataset spanning 17 years to identify the contributing factors to collision severity and suggests measures for improvement.

## Dataset
[Dataset Link](https://data.sfgov.org/Public-Safety/Traffic-Crashes-Resulting-in-Injury/ubvf-ztfx/about_data)
The dataset encompasses traffic crash data from 2005 to 2022, obtained from multiple sources like the SFPD’s Interim Collision System and the Statewide Integrated Transportation Record System, covering various aspects of collisions, including environmental and vehicle factors.

## Technologies
- Python
- NumPy
- Pandas
- Matplotlib

## Methodology
Following the CRISP-DM approach, we conducted extensive data preparation, exploratory data analysis, and applied machine learning models including clustering, outlier detection, and classification to predict collision severity and identify key factors contributing to severe accidents.

### Key Techniques Used
- Clustering (K-means, DBSCAN, Agglomerative Clustering)
- Outlier Detection (Local Outlier Factor, Isolation Forest, One-Class SVM)
- Classification (Random Forest, Decision Trees, Naïve Bayes, SVM)

## Getting Started
1. Clone the repository.
2. Explore the Jupyter Notebooks to understand the data preprocessing, model building, and evaluation process.

## Results
The analysis revealed that Random Forest models, particularly when trained on oversampled datasets, provided the highest accuracy in predicting collision severity. The project identified significant factors contributing to collision severity, such as time of day and involvement of pedestrians, providing insights for targeted preventive measures.

## Societal Impact
The findings offer valuable insights for the SFPD and public safety organizations, suggesting that strategic interventions focused on identified risk factors could significantly reduce traffic-related injuries and fatalities, supporting San Francisco's Vision Zero initiative.

## Acknowledgements
Thanks to DataSF for providing the dataset and opportunity to work on this project.

<!-- ## Usage
Instructions on how to set up the environment, install dependencies, and run the project are included.

## Acknowledgments
Thanks to all contributors and organizations that supported this project. -->

