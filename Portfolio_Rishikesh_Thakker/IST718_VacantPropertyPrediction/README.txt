Project Title: Vacant Property Prediction and Pattern Analysis in Syracuse

Course: IST718 – Big Data Analytics

Team Members: 
- Rishikesh Thakker
- Eric Lee
- Ari Fazlija
- Rajat Rohilla

Project Summary:
This project aimed to predict and analyze property vacancies in the City of Syracuse using integrated datasets including property records, crime statistics, and code violation reports.

The project followed a full data science lifecycle, applying:
- Data integration and cleaning using PySpark on Databricks.
- Feature engineering with PySpark UDFs and SQL transformations.
- Unsupervised learning using K-Means clustering and PCA for segmenting neighborhoods.
- Supervised learning using Random Forest classifiers to predict vacancy probabilities.

The analysis provided actionable insights to city officials to proactively intervene in at-risk neighborhoods.

Software and Tools Required:
- Microsoft PowerPoint or Google Slides to view the presentation.
- PySpark, and Python 3.8+ environment if replicating data processing and model training workflows.


Key Results:
- Random Forest achieved an AUC of 0.89 initially; 0.87 after oversampling.
- Precision, recall, and F1 scores indicated strong predictive ability even after addressing class imbalance.
- Clustering analysis revealed four key high-risk neighborhoods with higher vacancy probabilities.
- A dashboard was developed for city officials to visualize and act on predictions.

Additional Notes:
- Data Sources: Syracuse Open Data Portal (property, violation, crime datasets).
- Ethical Considerations: Analyzed and discussed potential biases in predictive modeling to avoid reinforcing historical disinvestment patterns.

