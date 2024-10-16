# Job Recommendation System

This project is a **Job Recommendation System** built using various machine learning models to predict and recommend relevant jobs based on user profiles and job listings. The system analyzes job titles, key skills, and other relevant data using TF-IDF vectorization and machine learning models.

## Table of Contents
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Performance Metrics](#performance-metrics)
- [How to Run](#how-to-run)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Features
- Recommends jobs based on user skills, job titles, and key skills using TF-IDF vectorization.
- Machine learning models used: Logistic Regression, K-Nearest Neighbors (KNN), Random Forest, Support Vector Machine (SVM), and Naive Bayes.
- Provides accuracy, precision, recall, and F1-score for each model.
- Displays ROC curve for model comparison.

## Technologies Used
- Python
- Flask (for web framework)
- Scikit-learn (for machine learning models)
- Pandas, Numpy (for data handling)
- Matplotlib, Seaborn (for visualization)

## Dataset
The dataset includes:
- 10,000 job listings with attributes such as Job Title, Key Skills, Experience, and Salary.
- 5,000 user profiles with fields like User Skills, Experience, and Education.

**Data Preprocessing**:
- TF-IDF vectorization is applied to job titles and key skills.
- Label encoding for target variables.

## Models Used
The following machine learning algorithms were trained and evaluated:
1. **Logistic Regression**  
   - Accuracy: 82.5%
   - Precision: 77.7%
   - Recall: 82.5%
   - F1 Score: 78.6%
   
2. **K-Nearest Neighbors (KNN)**  
   - Accuracy: 72.4%
   - Precision: 71.2%
   - Recall: 72.4%
   - F1 Score: 70.3%

3. **Random Forest** *(Best Performer)*  
   - Accuracy: 88.7%
   - Precision: 86.8%
   - Recall: 88.7%
   - F1 Score: 87.0%

4. **Support Vector Machine (SVM)**  
   - Accuracy: 88.3%
   - Precision: 85.7%
   - Recall: 88.3%
   - F1 Score: 86.6%

5. **Naive Bayes**  
   - Accuracy: 44.1%
   - Precision: 35.5%
   - Recall: 44.1%
   - F1 Score: 30.7%

## Performance Metrics
- **Random Forest** provided the best results with an accuracy of 88.7% and the highest F1 Score of 87.0%.
- The performance of each model was evaluated using 5-fold cross-validation.
- **ROC Curves** were plotted for each model to visualize their performance.

## Contributors

We would like to acknowledge the contributions of the following people who helped in building this project:

- [Disha Wankhede](https://github.com/Disha3112)
- [Om Karadkar](https://github.com/KaradkarOm)
- [Ameya Katdare]
- [Sanket Lohgaonkar]
- [Shubham Waghmare]

