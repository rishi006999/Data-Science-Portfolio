Project Title: Netflix Movie Recommendation System

Course: IST707 – Applied Machine Learning

Team Members:
- Rishikesh Thakker

Project Summary:
This project focused on developing a personalized movie recommendation system using user-item ratings from the Netflix dataset. The goal was to predict user preferences and improve content discovery by building scalable and accurate recommendation models.

The project implemented:
- Traditional collaborative filtering methods such as KNN with Means.
- Matrix factorization techniques using Singular Value Decomposition (SVD).
- Custom deep learning architectures (KNNNet and SVNet) for advanced feature interaction modeling.

The models were trained and evaluated based on RMSE and validation loss, with deep learning models showing improved performance over traditional methods.

Software and Tools Required:
- Microsoft Word to view the project report.
- (Optional) Python 3.8+ environment with libraries such as:
  - Surprise (for collaborative filtering)
  - Scikit-learn
  - TensorFlow/Keras (for deep learning models)
  - Pandas
  - Matplotlib for visualizations

How to View:
- Open Netflix_Recommendation_Project_Report 2.docx to read the full description of the recommendation system and modeling outcomes.

Key Results:
- SVD model achieved a validation loss of approximately 0.83, outperforming KNN with Means (~0.86).
- Deep learning models (KNNNet and SVNet) showed better generalization and lower RMSE across testing sets.
- Project demonstrated hybrid recommendation strategies to mitigate cold-start problems.

Additional Notes:
- Data Source: Netflix movie ratings dataset.
- Future Scope: Expanding to hybrid content-based + collaborative filtering models and real-time streaming recommendation systems.
- Ethical Considerations: Monitored diversity in recommendations to avoid reinforcing filter bubbles or popularity bias.

