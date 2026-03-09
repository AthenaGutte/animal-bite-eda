# Animal Bite Incident Analysis 🐾

🚧 **Project Status:** In Progress

This project explores patterns in reported animal bite incidents using exploratory data analysis (EDA) and machine learning techniques. The goal is to understand trends in animal bite reports and investigate which animal breeds are most frequently associated with bite incidents.

---

## 📊 Dataset

The dataset contains records of reported animal bite incidents and includes information such as:

- Date of bite
- Animal species and breed
- Animal gender and color
- Vaccination status
- Body part bitten
- Rabies test outcomes
- Location information (ZIP code)

Each row represents a single reported animal bite incident.

---

## 🎯 Project Goals

This project aims to answer questions such as:

- Which animal breeds are most frequently involved in bite incidents?
- Which animal species cause the most bites?
- Which body parts are most commonly bitten?
- Are there seasonal patterns in animal bite incidents?
- Can we predict the **breed of the animal involved in a bite** using available features?

---

## 🛠 Tools & Technologies

- **Python**
- **Pandas** – data cleaning and analysis
- **NumPy** – numerical operations
- **Matplotlib / Seaborn** – data visualization
- **Scikit-learn** – machine learning models
- **Google Colab** – development environment

---

## 📈 Project Workflow

### 1. Data Cleaning
- Handle missing values
- Replace missing categorical values with `"UNKNOWN"`
- Remove columns with extremely high missing data
- Extract useful features from date fields (e.g., bite year and month)

### 2. Exploratory Data Analysis (EDA)
- Distribution of animal species
- Distribution of animal breeds
- Bite location analysis
- Gender distribution of biting animals
- Seasonal patterns in bite incidents

### 3. Feature Engineering
- Encode categorical variables
- Create derived time features (year, month)
- Prepare dataset for machine learning

### 4. Machine Learning
Train models to predict **animal breed** based on bite incident characteristics, including:

- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forest (planned)

### 5. Model Evaluation
Models will be evaluated using metrics such as:

- Accuracy
- Precision / Recall
- Confusion Matrix

---

## 📁 Repository Structure
animal-bite-eda
│
├── Health_AnimalBites.csv
├── bites_eda.ipynb
└── README.md

---

## 📌 Current Progress

- Dataset exploration
- Data cleaning and preprocessing
- Handling missing values
- Initial exploratory data analysis and visualizations

**Upcoming work:**
- Feature encoding
- Machine learning model training
- Model comparison and evaluation

---

## 🚀 Future Improvements

- Improve feature engineering for better model performance
- Build a predictive model for bite incident characteristics
- Explore geographic bite patterns using location data
- Create an interactive dashboard for visualizing bite trends

---

## 👩‍💻 Author

**Athena Gutte**  
Computer Engineering Student interested in AI, Machine Learning, and Data Science.

GitHub:  
https://github.com/AthenaGutte
