# 💼 Employee Salary Prediction

This project is a machine learning web app that predicts the salary of an employee based on features like age, gender, education level, job title, and years of experience. Built using **Random Forest Regressor**, the app is deployed via **Streamlit** for a clean and interactive user interface.

---

## 📊 Project Overview

- Predict employee salary based on input features
- Trained using Random Forest Regressor
- Deployed using Streamlit
- Encodes categorical data using LabelEncoder
- Visualizes residual error distribution
- Displays model evaluation metrics like R² score and Mean Squared Error

---

## 🧠 Technologies Used

| Tool/Library     | Purpose                                |
|------------------|----------------------------------------|
| Python           | Core programming language              |
| Pandas           | Data handling                          |
| NumPy            | Numerical operations                   |
| Scikit-learn     | Machine learning modeling              |
| Matplotlib       | Data visualization                     |
| Streamlit        | Front-end web app                      |
| Pickle           | Saving/loading trained model & encoders|

---

## 🗂️ Project Structure

📁 Employee-Salary-Prediction/
│
├── Salary Data.csv # Dataset
├── model_train.ipynb # Jupyter Notebook for training
├── salary_model.pkl # Trained Random Forest model
├── label_encoders.pkl # Encoded mappings for categorical features
├── app.py # Streamlit web app
├── requirements.txt # Python dependencies
└── README.md # Project documentation
🔍 Example Inputs
Age: 30

Gender: Female

Education Level: Master's

Job Title: Data Analyst

Years of Experience: 5

📈 Model Evaluation
Model Used: RandomForestRegressor

Metrics:

R² Score: ~0.85

Mean Squared Error: ~2200000

Model performs well on general patterns but may vary with unseen job titles.

📌 Features
Interactive input sliders & dropdowns

Clean and responsive UI

Simulated residual plot

Encoded preprocessing handled internally

Helpful sidebar with usage info

🤝 Contributing
Contributions, suggestions, or feature requests are welcome!
Feel free to fork the repo and submit a pull request.

👤 Author
Komal Kumari

