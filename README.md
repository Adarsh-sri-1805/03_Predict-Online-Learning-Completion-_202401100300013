# 03_Predict-Online-Learning-Completion-_202401100300013
Online Course Completion Prediction
Problem Statement
The goal of this project is to develop a predictive model that classifies whether a learner will successfully complete an online course. The classification is based on activity logs, which include data on the learner’s engagement, such as videos watched, assignments submitted, and forum posts made. By analyzing these activity patterns, we aim to provide insights into learner behavior and predict whether they will complete the course.

Dataset
The dataset contains information about learner activities and their course completion status. The key features include:

videos_watched: Number of videos watched by the learner during the course.

assignments_submitted: Number of assignments submitted by the learner.

forum_posts: Number of posts made by the learner in the course’s online forum.

completed: Whether the learner successfully completed the course (1 for completed, 0 for not completed).

Data Columns

Column Name	Description
videos_watched	Number of videos the learner has watched.
assignments_submitted	Number of assignments the learner has submitted.
forum_posts	Number of posts made by the learner in the course forum.
completed	Target variable indicating whether the course was completed (1) or not (0).
Objective
Input: The features videos_watched, assignments_submitted, and forum_posts.

Output: The target variable completed, indicating if the learner will complete the course (1) or not (0).

Approach
Data Preprocessing: Clean the dataset and prepare the data for model training.

Model Training: Use machine learning algorithms such as Logistic Regression, Decision Trees, or Random Forests to train the model.

Model Evaluation: Evaluate the model’s performance using accuracy, precision, recall, and F1 score.

Insights: Use the trained model to gain insights into the factors that influence course completion.

Tools and Libraries
Python

Pandas: Data manipulation

Scikit-learn: Machine learning models and metrics

NumPy: Numerical operations

Matplotlib/Seaborn (Optional for visualization)
#RESULT-
The code predicts the required values and gives the following output
![image](https://github.com/user-attachments/assets/8c76df53-a6c1-4dee-8df4-7751e5e42d1a)
![image](https://github.com/user-attachments/assets/fc164008-a3c5-4b66-8906-989872bbf7dc)
