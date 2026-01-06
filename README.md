🍽️ Restaurant Intelligence System using Machine Learning
Python
License

A Restaurant Intelligence System built with Python and Machine Learning that aims to make the restaurant industry smarter and more data-driven.

This project solves three key problems:

⭐ Rating Prediction – Predict restaurant ratings using ML models.
🏙️ Restaurant Recommendation – Suggest restaurants to users based on preferences.
🍜 Cuisine Classification – Automatically classify restaurants into cuisines.
It demonstrates how data science and machine learning can be applied to the food & hospitality industry for real-world impact.

🎯 Project Objectives
Build a predictive model for restaurant ratings to estimate customer satisfaction.
Create a recommendation system to help users discover restaurants they’ll love.
Develop a classification system to organize restaurants based on cuisines.
Perform end-to-end ML pipeline: Data cleaning → Feature engineering → Model training → Evaluation.
📊 Dataset Information
The project uses a dataset (Dataset.csv) containing restaurant-related attributes such as:

Restaurant Name & Location
Cuisines Offered
Cost Information
Aggregate Ratings & Votes
Customer Reviews
The dataset undergoes cleaning, preprocessing, and feature engineering before being used for modeling.

📌 Tasks Breakdown
🔹 Task 1: Rating Prediction
Goal: Predict restaurant ratings based on various features.

Steps Involved:

Data Cleaning & Preprocessing (handle missing values, encode categorical variables, normalize data).
Feature Engineering (extract insights from cuisines, location, price range).
Model Building (Linear Regression, Decision Trees, Random Forest, Gradient Boosting).
Model Evaluation (RMSE, MAE, R² Score).
✅ Outcome: A model that predicts customer ratings for any restaurant.

🔹 Task 2: Restaurant Recommendation
Goal: Recommend relevant restaurants to users based on their preferences.

Steps Involved:

Data Preprocessing (cuisine, location, price).
Feature extraction using TF-IDF / CountVectorizer.
Similarity computation using Cosine Similarity.
Content-Based Recommendation (suggests top-N similar restaurants).
✅ Outcome: Personalized restaurant recommendations.

🔹 Task 3: Cuisine Classification
Goal: Classify restaurants into cuisine categories.

Steps Involved:

Text Preprocessing (tokenization, stopword removal, lemmatization).
Vectorization (Bag of Words / TF-IDF).
Model Training (Logistic Regression, Naive Bayes, Random Forest, SVM).
Evaluation (Accuracy, Precision, Recall, F1-score).
✅ Outcome: Automated cuisine classification for organizing and filtering restaurants.

🛠️ Tech Stack
Python 3.7+
Jupyter Notebook
Libraries:
Data Handling → pandas, numpy
Visualization → matplotlib, seaborn
ML Models → scikit-learn
NLP → nltk, scikit-learn (TF-IDF, CountVectorizer)
⚙️ Installation & Setup
Clone the repository:

git clone https://github.com/Prajjwalsen/Restaurant-Intelligence-System-using-Machine-Learning.git
cd Restaurant-Intelligence-System-using-Machine-Learning
Install dependencies:

pip install -r requirements.txt
(If requirements.txt is missing, manually install: pandas, numpy, scikit-learn, matplotlib, seaborn, nltk.)

Run notebooks:

jupyter notebook
Open:

Task1_RatingPrediction.ipynb → Task 1
Task2_RestaurantRecommendation.ipynb → Task 2
Task3_CuisineClassification.ipynb → Task 3
All_Tasks.ipynb → Combined workflow
📂 Project Structure
Restaurant-Intelligence-System-using-Machine-Learning/
│
├── All_Tasks.ipynb                          # Combined notebook
├── Task1_RatingPrediction.ipynb    # Task 1
├── Task2_RestaurantRecommendation.ipynb # Task 2
├── Task3_CuisineClassification.ipynb    # Task 3
├── Dataset.csv                              # Restaurant dataset       
└── README.md                                # Documentation
🚀 Workflow Summary
Data Understanding – Explore dataset with EDA & visualization.
Preprocessing – Clean, normalize, encode categorical data.
Feature Engineering – Extract insights from text and numerical data.
Modeling – Apply ML algorithms for regression, classification, and recommendations.
Evaluation – Assess using relevant metrics.
Reproducibility – Organized notebooks for all tasks.
📊 Expected Outcomes
✅ Accurate restaurant rating prediction.
✅ Effective restaurant recommendation system.
✅ Reliable cuisine classification model.
✅ Demonstration of ML in food & hospitality industry.
🤝 Contributing
Contributions are welcome! 🚀

Fork the repository
Create a new branch (feature-xyz)
Commit your changes
Push to your fork
Open a Pull Request
📜 License
This project is licensed under the MIT License – see the LICENSE file for details.

🙌 Author
Sachin kumar sahu
B.Tech CSE (AI & DS) | Data Science & AI Enthusiast
