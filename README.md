# **Airline Customer Satisfaction Prediction**

## **Project Overview**

This project aims to predict customer satisfaction for airlines based on various factors such as flight experience, service quality, and demographics. By analyzing customer feedback and flight details, we can classify whether a passenger is satisfied or dissatisfied with their airline experience.

## **Dataset**

The dataset used for this project contains information about airline passengers, including:

- **Demographics:** Age, Gender, Customer Type

- **Travel Details:** Class, Type of Travel, Flight Distance

- **Service Ratings:** Inflight entertainment, Onboard service, Seat comfort, Food & drink, etc.

- **Timeliness Factors:** Departure and Arrival delay times

- **Target Variable:** Satisfaction level (Satisfied / Dissatisfied)

## **Project Workflow**

1. **Data Collection & Exploration:** Load and explore the dataset.

2. **Data Preprocessing:** Handle missing values, encode categorical variables, and normalize numerical features.

3. **Exploratory Data Analysis (EDA):** Visualize trends and correlations within the data.

4. **Feature Engineering:** Select relevant features for model training.

5. **Model Building:**

- Train multiple machine learning models (Logistic Regression, Decision Tree, Random Forest, etc.).

- Compare model performance using evaluation metrics like Accuracy, Precision, Recall, and F1-score.

6. **Hyperparameter Tuning:** Optimize model parameters for better performance.

7. **Model Deployment:** Deploy the best-performing model as a web application (if applicable).

## **Technologies Used**

- **Programming Language:** Python

- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

- **Modeling Techniques:** Machine Learning (Classification Algorithms)

## **How to Run the Project**

### **1.Clone the repository:**

git clone https://github.com/PriyankaKumari-123-82/Airline-Customer-Satisfaction-Prediction.git
cd airline-satisfaction-prediction

### **2.Install dependencies:**

pip install -r requirements.txt

### **3.Run the Jupyter Notebook or Python script to train the model:**

jupyter notebook

### **4.To deploy** (if applicable),
use Flask/Django or streamlit.

## **Results & Insights**

- Identified key factors influencing airline customer satisfaction.

- Achieved an accuracy of 94% (to be updated with actual results).

- Developed a model that helps airlines enhance customer experience based on data-driven insights.
 
## **Future Scope**

- Integrate deep learning techniques for improved accuracy.

- Expand dataset to include real-time customer feedback.

- Develop a live dashboard for visualization and analysis.

## **License**
This project is licensed under the MIT License - see the LICENSE file for details.
