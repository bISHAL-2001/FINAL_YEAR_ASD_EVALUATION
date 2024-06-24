
# Final Year Project: Autism Spectrum Disorder (ASD) Evaluation
Autism Spectrum Disorder (ASD) is a complex developmental condition marked by persistent challenges in social interaction, communication, and restrictive, repetitive
behaviors. These challenges can significantly impact various aspects of an individual's life, including education, employment, and social relationships. Early diagnosis and
intervention are crucial, as they can greatly improve long-term outcomes for children with ASD. In this project, we present a novel application designed to assist in the early detection and diagnosis of ASD in children aged 1.5 to 5 years. Our app leverages a Support Vector Classifier (SVC) model trained on relevant data to assess the likelihood and typicalness of ASD. The user-friendly interface allows parents and healthcare providers to input necessary data, which the SVC model analyzes to provide a preliminary diagnosis. Furthermore, based on the model's assessment, the app recommends a customized level of therapy for the child, promoting early intervention and personalized treatment plans.

## Problem Statement
The early and accurate detection of ASD is crucial for effective intervention and support. Traditional diagnostic methods often rely on extensive behavioral assessments, which can be time-consuming and require specialized expertise. In recent years, machine learning techniques have shown promise in improving diagnostic accuracy and efficiency. This research aims to develop a robust predictive model for ASD detection using the Support Vector Classification (SVC) algorithm. By leveraging a comprehensive dataset that includes real and augmented samples collected from sources such as Kaggle, the CDC Autism Data Visualization Tool, and the University of Cambridge, this study seeks to identify key
behavioral and demographic features that contribute to ASD diagnosis. Additionally, the study will employ Recursive Feature Elimination (RFE) to optimize feature selection,
thereby enhancing the model's performance and reducing computational complexity. The primary objectives of this research are to evaluate the effectiveness of the SVC algorithm in ASD detection, to determine the most significant predictive features, and to compare the SVC model's performance against other machine learning approaches such as Artificial Neural Networks (ANN) and Random Forest (RF).


### Q-CHAT 10 Questions as per University of Cambridge

![Q-CHAT10](.images/image.png)


## SVC (Support Vector Classifier)
Before we go forward it is very essential to know what SVC means and its utility in the Machine Learning field. 
Support Vector Classification (SVC) is a supervised machine learning algorithm used for
classification tasks. It works by finding the optimal hyperplane that best separates data
points of different classes with the maximum margin. This hyperplane is influenced by
support vectors, which are the closest data points to the hyperplane from each class. By
maximizing the margin, SVC improves generalization to unseen data. Additionally, SVC
can handle non-linear classification problems using the kernel trick, which transforms the
input space into higher dimensions where a linear separator can be found, making it a
versatile and powerful tool for various classification problems.

Support Vector Classification (SVC) is often favored over Logistic Regression, Random Forest, and Gradient Boosting due to its capability to manage high-dimensional, complex datasets and non-linear relationships using the kernel trick. SVC excels at maximizing the margin between classes, which enhances generalization to unseen data. While Logistic Regression is highly interpretable, it is inherently linear and less effective in high-dimensional spaces without feature engineering. Random Forests can handle non-linearity and provide feature importance, but they may become computationally intensive and less interpretable with many features. Gradient Boosting is powerful for non-linear problems but requires extensive tuning and can overfit if not properly regularized.

Therefore, SVC's robust handling of high-dimensional data and non-linear decision boundaries, coupled with its robustness and impressive accuracy scores of 95.986% in training and 93.439% in validation, makes it a strong choice for many classification tasks.

Learn more from sources:
1. [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2021/06/support-vector-machine-better-understanding/)
2. [scikit-learn](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html)
3. [Medium](https://towardsdatascience.com/diving-into-c-support-vector-classification-221ced32e4b4)
