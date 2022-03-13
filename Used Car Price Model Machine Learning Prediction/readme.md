# Used Car Price Model Machine Learning Prediction
* Build model to help business team to providing recommendations for used car prices based on historical purchase data from the previous 2 years in America
* This dataset is obtained from [Used Car Auction Prices | Kaggle](https://www.kaggle.com/tunguz/used-car-auction-prices)
* Data Cleansing --> Delete all missing value because the amount does not reach 5% of the total data
* Engineered features to optimizing the learning process of model
* Train model with 4 different algorithms
* Provide an example of implementing model into company website to predict the price of a used car

## Problems
* **Conventional Business Process Consumes Too Much Time** (The screening and negotiation process takes a long time, so customers become hesitant and tend not to sell their cars to our company)
* **Lack of Trust from Customers due to Staff’s Subjectivity** (The company determines the purchase price of a used car is not standard (not in accordance with the actual condition of the car) so that the price of a used car is determined from a biased perspective by each staff)

## Goal & Objective
* To help companies build machine learning models to determine the purchase price of a used car that can be standardized based on actual conditions

## Some Insights from the dataset
1. The most sought-after used cars are used cars with a medium price segment<br>
![image](https://user-images.githubusercontent.com/99066590/158050238-79931b81-fd10-49f7-ad5f-c67567b06d78.png)<br>
2. Top 5 most sought-after used car manufacturers<br>
![image](https://user-images.githubusercontent.com/99066590/158050346-4a88a740-79c9-4cf5-801c-fac3104d9b22.png)<br>
3. The 5 most sought-after used car body types<br>
![image](https://user-images.githubusercontent.com/99066590/158050426-cbe836e3-0001-4700-916c-859ce6c39d89.png)<br>

# ML Modeling
Split the data into train set & test set (size is 70%-30%).
Trained the model with 4 different algorithms and evaluated them with **MAE**,**RMSE**,**MSE**,**R2 Score** .The model was trained with:
* Linear Regression
* Decision Tree
* Random Forest
* XGBoost

# Model Evaluation
![image](https://user-images.githubusercontent.com/99066590/158050575-d59c5766-e005-4746-b554-5b56be3fcea2.png)
* Selected Model<br>
![image](https://user-images.githubusercontent.com/99066590/158050655-cfd284a2-3084-46bb-aa46-2e12431cf453.png)<br>

# Business Insight & Recommendation
* Implementing a machine learning model that has been built by the data team into the company's website to predict the price of a used car based on the conditions and features of the car provided. Here is an example of what the website looks like:<br>
![image](https://user-images.githubusercontent.com/99066590/158050712-73688858-5a2e-4c23-a1f9-23f8a99a39d8.png)<br>
* The price of used cars based on machine learning models is expected to increase the accuracy and transparency of car prices so that there is no underpricing and overpricing so that customers get fair prices and do not feel cheated.

# Team Behind This Project
* This is our final project to finish learning path for Data Science in [Rakamin Academy](https://rakamin.com/)<br>

**The Team Member**<br>
| Member | LinkedIn|
| --- | --- |
| **Hafizh Adi Prasetya (as Mentor)** | https://www.linkedin.com/in/hafizhadi/ |
| **Joshua Abisha (as Leader)** | https://www.linkedin.com/in/joshuaabisha/ |
| **Daniel Jeffry** | https://www.linkedin.com/in/daniel-jeffry-a91760203/ |
| **Muhammad Arif Budiman** | http://www.linkedin.com/in/m-arifbudiman21 |
| **Muhammad Faisal** | https://www.linkedin.com/in/muhammad-faisal-391839107 |
| **Queenta Rahatesa** | https://www.linkedin.com/in/queenta-rahatesa-80b648150 |
| **Tri Utomo** | https://www.linkedin.com/in/tri-utomo-407289200 |
