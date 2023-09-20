# Blood-Diffusion-Prediction
classification-project


##  Summary

This report outlines the data-driven approaches used to predict blood donation behavior. The dataset used for this analysis is named 'transfusion.csv.' We applied three different machine learning algorithms: K-Nearest Neighbors (KNN), Support Vector Machine (SVM), and Decision Tree Classifier, to predict whether an individual would donate blood in March 2007 based on various features like recency, frequency, monetary value, and time since the last donation.

## Data Loading and Preprocessing

1. **Data Loading**: The analysis began with loading necessary libraries, including Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn, and importing the 'transfusion.csv' dataset.

2. **Data Exploration**: An initial exploration of the dataset involved examining the first few rows using `BloodDonation.head()` and generating a pair plot using Seaborn to visualize relationships between variables.

## K-Nearest Neighbors (KNN) Approach

### Iteration 1
3. **Data Splitting**: The dataset was divided into features (X) and the target variable (Y). Then, a train-test split was performed, with a test size of approximately 33.16% of the data.

4. **Data Scaling**: The feature data was standardized using the StandardScaler.

5. **Model Building**: A K-Nearest Neighbors classifier was instantiated with k=23, and the model was fitted to the training data.

6. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 81.05%.

### Iteration 2
7. **Data Splitting**: The same steps as in Iteration 1 were repeated with a different random state.

8. **Model Building**: A new K-Nearest Neighbors classifier was instantiated with k=17, and the model was fitted to the training data.

9. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 76.21%.

### Iteration 3
10. **Data Splitting**: The same steps as in Iteration 2 were repeated with another random state.

11. **Model Building**: A new K-Nearest Neighbors classifier was instantiated with k=17, and the model was fitted to the training data.

12. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 80.24%.

### K-Nearest Neighbors (KNN) Conclusion
The K-Nearest Neighbors algorithm was applied in three iterations with different random states and k-values. The average accuracy of the KNN approach was approximately 79.17%.

## Support Vector Machine (SVM) Approach

### Iteration 1
13. **Model Building**: A Support Vector Machine classifier with a linear kernel was instantiated and fitted to the training data.

14. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 77.42%.

### Iteration 2
15. **Model Building**: The same steps as in Iteration 1 were repeated with a different random state.

16. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 76.21%.

### Iteration 3
17. **Model Building**: The same steps as in Iteration 2 were repeated with another random state.

18. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 74.60%.

### Support Vector Machine (SVM) Conclusion
The Support Vector Machine algorithm was applied in three iterations with different random states. The average accuracy of the SVM approach was approximately 76.08%.

## Decision Tree Classifier Approach

### Iteration 1
19. **Model Building**: A Decision Tree classifier with a maximum depth of 3 was instantiated and fitted to the training data.

20. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 79.84%.

### Iteration 2
21. **Model Building**: The same steps as in Iteration 1 were repeated with a different random state.

22. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 76.21%.

### Iteration 3
23. **Model Building**: The same steps as in Iteration 2 were repeated with another random state.

24. **Model Evaluation**: The model's accuracy, confusion matrix, and classification report were generated for the test data. The accuracy achieved in this iteration was approximately 77.42%.

### Decision Tree Classifier Conclusion
The Decision Tree Classifier was applied in three iterations with different random states. The average accuracy of the Decision Tree approach was approximately 77.82%.

## Overall Conclusion

The analysis demonstrates the application of various data-driven approaches to predict blood donation behavior. The K-Nearest Neighbors, Support Vector Machine, and Decision Tree Classifier algorithms were evaluated. The average prediction accuracy for each approach was as follows:

- K-Nearest Neighbors (KNN): Approximately 79.17%
- Support Vector Machine (SVM): Approximately 76.08%
- Decision Tree Classifier: Approximately 77.82%

The Decision Tree Classifier showed the highest average accuracy among the three algorithms. Further tuning and optimization of these models may improve predictive performance.
