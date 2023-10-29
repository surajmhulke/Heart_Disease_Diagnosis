## Heart Disease Diagnosis
This project is designed to Heart Disease Diagnosis using Machine Learning techniques. The Heart Disease Diagnosis is a data science project aimed at utilizing advanced data analytics and machine learning techniques to enhance the accuracy of predicting Heart disease premiums for individuals. 

## Introduction About Project
The "Heart Disease Diagnosis Project" is a critical and potentially life-saving endeavor that leverages data, technology, and medical expertise to improve the early detection and diagnosis of heart disease. Heart disease, including conditions like coronary artery disease, heart failure, and arrhythmias, is a leading cause of morbidity and mortality worldwide. Early diagnosis and intervention are crucial for improving patient outcomes and reducing the burden of heart disease on individuals and healthcare systems.

## Tools and Libraries
## Tools
•	Python
•	Jupyter Notebook
•	Flask
•	HTML
•	CSS
•	JavaScript
•	Heroku
•	GitHub
## Libraries
•	Pandas
•	Scikit-Learn
•	Numpy
•	Seaborn
•	Matplotlib
## Data Collection
For this project, we utilized data available on Kaggle. The dataset contains 7 columns and 1338 rows, featuring key information about the properties ,
•	age 
•	sex
•	cp 
•	trestbps 
•	chol
•	fbs 
•	restecg 
•	thalach
•	exang 
•	oldpeak 
•	slope 
•	ca
•	thal
•	target

#### Project Flow
## Exploratory Data Analysis (EDA)
## Data Cleaning
We started with 14 columns but removed unnecessary Data cleaning included:
•	Handling missing values
•	Removing corrupted data
•	Date and text parsing
## EDA
Exploratory Data Analysis (EDA) is a critical initial step in the data analysis process. It involves investigating, summarizing, and visualizing the main characteristics of a dataset. EDA helps you understand your data, identify patterns, relationships, anomalies, and insights, which are crucial for making informed decisions and formulating hypotheses for more advanced analyses.
## Data Collection and Inspection:
Gather the dataset you intend to analyse.	
Inspect the data to ensure it's in a usable format.
Check for missing values, duplicates, and outliers
## Feature Engineering
We discovered outliers in a bmi column applied the IQR method for outlier removal. 
We have replaced outliers with upper_tail , now dataset having no outlier checked from using seaborn library.
## Data Normalization
We used min-max normalization to scale numerical features between 0 and 1.
## Model Deployment
The model was integrated into a user-friendly web interface using HTML, CSS, and Flask.
## Model Conclusion
The model predicts housing prices with 85% accuracy on test data.
## Project Innovation
•	User-friendly
•	Open source
•	High accuracy
•	GUI-based application
## Limitations and Next Steps
## Limitations:
•	Lack of a mobile application
•	Potential for further accuracy improvements
•	Large model size (~310MB)
•	Limited feature set
## Next Steps:
•	Develop a mobile application
•	Reduce model size using Principal Component Analysis (PCA)


