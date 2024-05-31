# Project Title: Youtube_Video_Popularity_Prediction with Interactions and without Interactions
# Project Overview
Youtube Video Popularity Prediction: Build a model to predict the popularity of a YouTube video based on various factors such as title, description, tags, view count, likes, and comments. This can help content creators optimize video attributes for better engagement.

# Goals and Objectives
To build a model that predicts the popularity of a YouTube video based on factors like title, description, tags, view count, likes, and comments, you can follow these steps:

1. Data Collection: Collect a dataset of YouTube videos with their associated attributes such as title, description, tags, view count, likes, and comments. You can obtain this data through the YouTube API and kaggle(US,CA,AU,IN). Provided the kaggle link below.

2. Data Preprocessing: Clean and preprocess the collected data. Perform tasks such as removing unnecessary characters, handling missing values, tokenizing text, removing stopwords, and converting categorical variables into numerical representations.

3. Feature Engineering: Extract relevant features from the textual data of the title, description, and tags. This can include word frequency, TF-IDF scores. Additionally, consider normalizing or scaling numerical features like view count, likes, and comments.

4. Splitting the Data: Split the dataset into training and testing sets. The training set will be used to train the popularity prediction model, while the testing set will be used to evaluate its performance.

5. Model Selection and Training: Choose an appropriate machine learning algorithm for popularity prediction, such as regression models (e.g., linear regression, Ridge regeression and XGBoost etc). Train the selected model on the training data.

6. Model Evaluation: Evaluate the trained model's performance using appropriate evaluation metrics such as mean squared error (MSE), root mean squared error (RMSE), or R-squared. This will help you assess how well the model predicts the popularity of YouTube videos.

7. Fine-tuning and Optimization: Fine-tune the model by experimenting with different hyperparameters and feature combinations. Consider techniques like cross-validation, grid search to optimize the model's performance.

9. Predicting Popularity: Use the trained model to predict the popularity of new YouTube videos based on their attributes. Provide insights and recommendations to content creators on optimizing video attributes to improve engagement and popularity.


# Key Milestones
. Milestone 1: Collect data

. Milestone 2: Data Preprocessing

. Milestone 3: Exploratory Data Analysis 

. Milestone 4: Development of Predictive model without interactions

. Milestone 5: Development of Predictive model with interactions

. Milestone 6: Final report and presentation of findings


[Link to kaggle dataset](https://www.kaggle.com/datasets/asaniczka/trending-youtube-videos-113-countries).
