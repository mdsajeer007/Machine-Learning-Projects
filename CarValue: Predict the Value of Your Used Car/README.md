# CarValue: Predict the Value of Your Used Car
# Problem Statement
Buying or selling a used car can be confusing and uncertain because traditional pricing methods like blue book estimates and mileage-based formulas often overlook important factors like the specific make, model, and options of a vehicle. This lack of detailed information leads to unfair deals and poor decision-making for buyers, sellers, and businesses involved. 


# Solution
To develop a web application that accurately predicts the sales price of a used car based on certain attributes.

# Description
The dataset was taken from Quickr it contains parameters like
* name: Model name
* company: Brand name
* year: Year of manufacture
* kms_driven: Distance the car has been driven
* fuel_type: Type of fuel the car uses for its engine

The image below displays the predicted price of a Hyundai Grand i10.

![Sample Predicted Car Price](https://github.com/mdsajeer007/Machine-Learning-Projects/blob/main/CarValue%3A%20Predict%20the%20Value%20of%20Your%20Used%20Car/predict.png)



# Project Workflow Overview:

* Scraped data from [Quickr.com](https://www.quikr.com/).
* Cleaned and analyzed the data.
* Developed a Linear Regression model with an R2 score of 0.84.
* Implemented the model into a Flask-based website for making predictions.

# How to Run
    1. Install the required packages listed in the "requirements.txt" file.
    2. Ensure all files from the repository are placed in a single folder.
    3. Run the "application.py" file.

# Tech stack
* Python - for building the machine learning model to predict prices
* HTML & CSS - for structure, styling and layout of webpages
* Javascript - for implementing dynamic interactive elements on the web pages
* Flask - for connecting the machine learning backend to the front-end UI
