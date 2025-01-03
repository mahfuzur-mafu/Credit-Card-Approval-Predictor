# Credit Card Approval Prediction

## Project Overview

This project aims to predict credit card approval using machine learning techniques. The goal is to build and evaluate various classification models to identify the best-performing model for accurate prediction.

### Key Steps:
1. **Data Preparation**  
   - Loading and merging credit card datasets (`Credit_card.csv` and `Credit_card_label.csv`).
   - Handling missing values by removing irrelevant columns and rows.
   - Checking for and removing duplicate entries.

2. **Exploratory Data Analysis (EDA)**  
   - Calculating descriptive statistics to understand the data.
   - Analyzing the average income by gender and visualizing with a bar plot.
   - Visualizing the credit approval status distribution using a pie chart.
   - Exploring relationships between features with visualizations like box plots and violin plots.
  
3. **Visualization**

Average Income by Gender

![image](https://github.com/user-attachments/assets/f3c5a39c-b0ee-4037-afa3-bceef0239e3f)

Credit Approval Status


![image](https://github.com/user-attachments/assets/18357ead-d79e-4494-911d-a1698fdba312)

Annual Income By Marital Status 


![image](https://github.com/user-attachments/assets/369eaec5-bc36-4650-a2b6-cf4e8e638ab8)

Birthday Count By Gender


![image](https://github.com/user-attachments/assets/63678d36-898e-48cb-8bf9-d84888bd176b)

Family Members By Marital Status 

![image](https://github.com/user-attachments/assets/499962a4-427f-46dd-967f-13852d814fb2)


Annual Income By Education 

![image](https://github.com/user-attachments/assets/494cd7b6-c629-43b7-9ff5-1dfdee5ff9c9)



4. **Feature Engineering and Selection**  
   - Selecting relevant features for model building (`Car_Owner`, `Propert_Owner`, `Annual_income`, `EDUCATION`, `label`).
   - Converting categorical features to numerical representations using label encoding.

5. **Model Building and Evaluation**  
Splitting the dataset into training and testing sets.
   - Standardizing data using `StandardScaler`.
   - Training and evaluating various classification models:
     - Logistic Regression
     - K-Nearest Neighbors (KNN) with `GridSearchCV` for hyperparameter tuning
     - Support Vector Machine (SVM) with `GridSearchCV`
     - Decision Tree with `GridSearchCV`
     - Random Forest with `GridSearchCV`
     - AdaBoost with `GridSearchCV`
   - Evaluating model performance using accuracy score.
  
    


6. **Results**

| Model                        | Accuracy Score |
|------------------------------|----------------|
| Logistic Regression           | 0.90           |
| K-Nearest Neighbors (KNN)     | 0.60           |
| Support Vector Classifier (SVC) | 0.80         |
| Decision Tree                 | 0.80           |
| Random Forest Classifier      | 0.85           |
| AdaBoost                      | 0.90           |

### Best Performing Models:
The **Logistic Regression** and **AdaBoost** models achieved the highest accuracy of **0.90**, making them the best-performing models for credit card approval prediction in this project.

---

## Usage

1. Clone the repository: 
2. Activate the virtual environment (if created): 
3. Run the Jupyter Notebook: 

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.
