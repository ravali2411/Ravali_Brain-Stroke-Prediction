# Ravali_Brain-Stroke-Prediction

Problem Specification:

The main aim is to predict the brain stroke of the person based on the input parameters of the that person. The problem is creating the model in such a way that the designed model should predict the true positives and true negatives properly and have very few false negatives.

Project Objective:

The objective of the project is to build CNN, Decision Tree, SVM, Naive-Bayes models that would predict if a subject had a chance of brain stroke or not and compare the accuracies and recall factors. We will be using accuracy and recall as metrics to justify the model’s performance.

Independent and Dependent variables:

Dependent variable: stroke.

Independent variables: gender, age, hyper_tension, heart_disease, ever_married, work_type, residence_type, avg_glucose_level, bmi, smoking_status

Splitting Data:

Here, we split the data into two sets. One is Training dataset, and one is Test dataset. 

Training Dataset: It is a subset to train the model.(70%)

Testing Dataset: It is the subset to test the trained model.(30%)

Data Preprocessing:

We have scaled, normalized, and then selected the appropriate columns and cleansed the inappropriate values and summarized the data for better understanding.

Model building:

1.Two Class Neural Network

2. Two Class Bayes Point Machine

3. Two Class Boosted Decision Tree

4.Two Class Super Vector Machine

Conclusion:

In this project, we proposed a system that enables the early detection and prediction of stroke disease based on machine learning techniques.

This is an important experimental result indicating that the early detection of stroke disease can be accurately predicted using Two Class Neural Networks as it is having accuracy of 0.908 and recall factor value of 0.321 which is higher compared to any other models.

In Health care analytics it is better to have few false negatives. And this model has less false negatives compared to any other models used in the project.

Further Improvement:

Further research and develop systems that provide more reliable and clinically interpretable stroke prediction results by conducting multi modal studies can be built by combining electronic medical recording (EMR) data, such as individual health checkups, with CT or MRI scans and interpretating the information.

Business Value:

The predominant value would be predicting whether the person will get affected by brain stroke or not by analyzing various input features incorporated in the design.

The other important value would be greater recall value with fewer false negatives as predicting a person will not get affected with brain stroke when person gets affected by brain stroke is not acceptable in health care analytics.
