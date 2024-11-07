# Bengaluru House Price Prediction using Ridge Regression

## Objective
The goal of this project is to predict house prices in Bengaluru based on various features such as location, size, number of bedrooms, and other property-related attributes. Ridge Regression, a regularized linear regression model, is used to reduce overfitting by applying a penalty on large coefficients, ensuring better generalization for predicting house prices.

## Methodology

### Data Collection
A real-estate dataset was collected, containing details about various properties in Bengaluru, including features like the area, number of rooms, amenities, and location.

### Data Preprocessing
The dataset was cleaned and preprocessed by handling missing values, encoding categorical features, and scaling numerical features for better model performance.

### Modeling with Ridge Regression
A Ridge Regression model was trained on the processed data, applying L2 regularization to the linear regression model to avoid overfitting and enhance generalization.

### Model Evaluation
The model achieved an accuracy of 82%, with performance evaluated using metrics such as Mean Squared Error (MSE) and R², demonstrating the effectiveness of Ridge Regression in predicting house prices accurately.

## Key Results
- The model achieved an **82% accuracy** in predicting house prices, indicating good generalization and performance.
- Ridge regularization improved the stability of the model by controlling the complexity and reducing overfitting.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## How to Run
1. Clone the repository:  
   `git clone https://github.com/Harsha-S-Naik/Bengaluru_House_Price_Prediction.git`
   
2. Install the required libraries:  
   `pip install -r requirements.txt`
   
3. Run the Jupyter Notebook to see model experiment:  
   `jupyter notebook`

4. Run the main.py to see the model in action:  
   `python main.py`

## Preview
![house](https://github.com/user-attachments/assets/f5356102-4fa0-470d-94d7-50bed4b65504)

# Hosted Link : 
  https://bengaluru-house-price-prediction-vxi3.onrender.com/
  - loading the website takes time

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


