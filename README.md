# CoreSpect-A_Product_verification_platform
Product Verification Prediction using Machine Learning and Sentiment Analysis
Project Overview
This project aims to predict whether a product is verified or not based on various features such as price, discount, rating, and customer reviews. The project involves data cleaning, feature engineering, sentiment analysis on reviews, and building a machine learning model to classify products as either verified (1) or not verified (0). The dataset includes product information, user reviews, and ratings.

Features
Data Cleaning: Handling missing values and removing duplicates to ensure data quality.
Sentiment Analysis: Analyzing customer reviews using TextBlob to classify reviews as positive, neutral, or negative.
Feature Engineering: Creating a verification label based on thresholds for ratings, discount percentages, review sentiment, and rating counts.
Machine Learning Model: Training a RandomForestClassifier to predict product verification status.
Evaluation: Assessing model performance using accuracy, classification reports, and confusion matrices.
Visualization: Correlation heatmap, distribution plots, and scatter plots to explore relationships in the data.
Dataset
The dataset contains the following columns:

product_id: Unique identifier for each product.
product_name: Name of the product.
category: Category of the product.
discounted_price: Discounted price of the product.
actual_price: Original price of the product.
discount_percentage: Percentage discount applied.
rating: Average rating of the product.
rating_count: Number of ratings received.
about_product: Product description.
user_id: Unique identifier for each user.
user_name: Name of the user.
review_id: Unique identifier for each review.
review_title: Title of the review.
review_content: Content of the review.
img_link: Image link for the product.
product_link: Product link.
Key Steps
Data Preprocessing: Handling missing values and duplicates.
Sentiment Analysis: Using TextBlob to extract sentiment polarity from review_content.
Feature Engineering: Creating a verification column based on thresholds for various features.
Model Training: Building and training a RandomForestClassifier.
Model Evaluation: Measuring model performance using accuracy, classification reports, and confusion matrices.
Visualization: Exploring relationships and distributions with correlation heatmaps, box plots, scatter plots, and more.
Results
The trained RandomForestClassifier achieves good performance in predicting product verification status. Sentiment analysis on reviews also helps improve the prediction by incorporating customer feedback into the decision-making process.

Technologies Used
Python: Programming language for data manipulation and machine learning.
Pandas: Data manipulation and analysis.
NumPy: Numerical operations.
TextBlob: Sentiment analysis.
Scikit-Learn: Machine learning algorithms and evaluation.
Matplotlib/Seaborn: Data visualization.
How to Run the Project
Clone the repository.
Install the required libraries using pip install -r requirements.txt.
Run the Jupyter Notebook to explore the data and train the model.
Modify thresholds or experiment with different models as needed.
Future Work
Experiment with different machine learning algorithms such as Logistic Regression, SVM, or Neural Networks.
Fine-tune hyperparameters for better model performance.
Explore other NLP techniques for sentiment analysis.
Integrate more advanced feature engineering techniques.
