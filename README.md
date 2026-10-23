# Skin Disorder Classification and Data Analysis

This project focuses on classifying skin disorders using machine learning on a dermatology dataset. It demonstrates how clinical and histopathological features can be used to build a predictive classification model.

## Problem
Skin disorders can be difficult to diagnose accurately because symptoms often overlap and require expert interpretation. Manual diagnosis can be time-consuming, subjective, and inconsistent. There was a need for a data-driven approach to support early identification and classification of skin conditions.

## Problem Faced
- Limited dataset size reduced generalization capability
- Missing values needed careful preprocessing
- Multiple disease classes made classification more complex
- Validation had to be handled carefully to avoid misleading results
- The project needed to stay research-focused without claiming medical diagnosis accuracy

## Solution
This project uses a machine learning workflow to:
- load and validate the dataset
- handle missing values
- explore feature patterns
- compare several classifiers
- evaluate model performance

Files in the repository:
- `PRCP-1027_Skin_Disorder_Analysis.ipynb` — full analysis, preprocessing, model comparison, and evaluation
- `dataset_35_dermatology (1).csv` — dermatology dataset used for training and testing

## Goal
To understand the dataset, compare predictive models, and assess how machine learning can support skin disorder classification in a research setting.

## Final Report
This project explored the problem of skin disorder classification using a structured dermatology dataset. The main objective was to determine whether machine learning models could accurately identify disease categories from clinical and histopathological features.

The analysis involved loading the dataset, checking data quality, handling missing values, and comparing several classification models. The workflow emphasized proper validation to reduce overfitting and ensure that the results were meaningful. The notebook also documented the limitations of the dataset and the risks of treating the model as a medical decision tool.

The project successfully demonstrates a practical machine learning workflow for multi-class classification. It shows that predictive models can capture patterns in the dataset and produce useful classification results. However, the study also highlights important challenges, including limited sample size, missing values, and the fact that the model is not a substitute for professional medical diagnosis.

Overall, the project is a strong research and learning exercise in data analysis and classification. It proves the feasibility of applying machine learning to dermatology data, while also emphasizing that real-world clinical deployment would require larger datasets, expert validation, and medical review.

## Conclusion
This project shows that machine learning can be effectively used for skin disorder classification on a structured dataset. It highlights the importance of data quality, preprocessing, and proper validation in medical-data analysis. However, the results should be viewed as research-oriented rather than clinical-grade diagnosis. For real-world healthcare use, a larger and more diverse dataset, expert review, and clinical validation would be required.
