# animal-bite-eda
Animal Bite Incident Analysis 🐾

🚧 Project Status: In Progress

This project explores patterns in reported animal bite incidents using exploratory data analysis (EDA) and machine learning techniques.
The goal is to understand trends such as which animals bite most frequently, where bites occur on the body, and how factors like vaccination status relate to rabies outcomes.


📊 Dataset

The dataset contains records of reported animal bite incidents and includes information such as:
	•	Date of bite
	•	Animal species and breed
	•	Animal gender and color
	•	Vaccination status
	•	Body part bitten
	•	Quarantine and test results
	•	Location information (ZIP code)

Each row represents a single animal bite incident.


🎯 Project Goals

This project aims to answer questions such as:
	•	Which animal species cause the most bite incidents?
	•	Which body parts are most commonly bitten?
	•	Are vaccinated animals less likely to test positive for rabies?
	•	Are there seasonal or geographic patterns in bite incidents?


🛠 Tools & Technologies
	•	Python
	•	Pandas – data cleaning and analysis
	•	NumPy – numerical operations
	•	Matplotlib / Seaborn – data visualization
	•	Scikit-learn – machine learning models
	•	Google Colab – development environment


📈 Project Workflow
	1.	Data Cleaning
	•	Handle missing values
	•	Convert "UNKNOWN" entries to NaN
	•	Standardize categorical variables
	2.	Exploratory Data Analysis (EDA)
	•	Distribution of animal species
	•	Bite location analysis
	•	Vaccination trends
	•	Rabies testing outcomes
	3.	Feature Engineering
	•	Transform and encode categorical variables
	•	Create derived features for modeling
	4.	Machine Learning
	•	Train and evaluate models including:
	•	Logistic Regression
	•	K-Nearest Neighbors
	•	Decision Tree
	5.	Model Evaluation
	•	Accuracy
	•	Precision / Recall
	•	Confusion Matrix


📁 Repository Structure

animal-bite-eda
│
├── Health_AnimalBites.csv
├── bites_eda.ipynb
└── README.md


📌 Current Progress
	•	Dataset exploration
	•	Initial data cleaning
	•	Preliminary EDA visualizations

Upcoming work:
	•	Feature engineering
	•	Machine learning model training
	•	Model comparison and evaluation


🚀 Future Improvements
	•	Build a predictive model for rabies test outcomes
	•	Create an interactive dashboard
	•	Expand analysis with geographic visualization


👩‍💻 Author

Athena Gutte
Computer Engineering Student interested in AI, Machine Learning, and Data Science.

GitHub: https://github.com/AthenaGutte
