
Folder highlights
Project used Logistic Regression to classify crop health from multispectral data, achieving 0.97 accuracy; red heatmaps show stress areas.

AI-Based Crop Health Monitoring Using Multispectral Data
Capstone Project Submission

1. Project Overview
This project predicts crop health using vegetation indices derived from drone multispectral data.
A machine learning model (Logistic Regression) is trained to classify crop health and generate
spatial stress heatmaps for drone-based monitoring.

2. Dataset
Synthetic Multispectral Crops Data.xlsx
Each row represents a spatial tile with vegetation indices and crop health label.

3. Model Used
Final Model: Logistic Regression
Reason: It achieved better ROC-AUC and F1-score compared to Random Forest on this dataset.

4. Folder Guide
- Heatmaps_and_Visualizations:
  Contains spatial stress heatmaps and plots.
- Model_Performance:
  Contains evaluation metrics and ROC curve.
- Video:
  Contains short explanation video.

5. Notebook
The full implementation is available in the Google Colab / Jupyter Notebook link submitted separately.

6. How to Interpret Results
Red/high values in heatmaps indicate stressed crop regions.
These areas should be prioritized for drone inspection and agronomic intervention.
