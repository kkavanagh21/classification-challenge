# classification-challenge

Email Spam Detection

This project aims to improve the email filtering system for an Internet Service Provider (ISP) by developing a machine learning model to accurately detect spam emails.

Project Overview

I used two supervised machine learning models to classify emails as spam or not spam:

Logistic Regression &
Random Forest

The Random Forest model performed better than the Logistic Regression model in detecting spam emails.

Files

spam_detector.ipynb: Jupyter notebook containing the code and analysis for the project.

spam-data.csv: The dataset used for training and testing the models.

Steps

Split the Data: The dataset was split into training and testing sets.

Scale the Features: The features were scaled to ensure the models perform optimally.

Logistic Regression Model: A logistic regression model was created, trained, and evaluated.

Random Forest Model: A random forest model was created, trained, and evaluated.

Evaluate the Models: The performance of both models was compared.

Findings

The Random Forest model had a higher accuracy in detecting spam emails compared to the Logistic Regression model.
This indicates that the Random Forest model is better at capturing the complex patterns in the data, making it a more effective choice for spam detection.

How to Run

Clone the repository:
bash
Copy code
git clone https://github.com/your-username/classification-challenge.git
Navigate to the project directory:
bash
Copy code
cd classification-challenge
Open the Jupyter notebook:
bash
Copy code
jupyter notebook spam_detector.ipynb
Follow the steps in the notebook to see the data processing, model training, and evaluation.

Conclusion

The findings suggest that the email data has complex patterns that are better captured by the Random Forest model, making it a more effective choice for spam detection. This indicates that leveraging more advanced models can significantly improve the performance of email filtering systems in practical applications.
