# MDPT_majorProject

🩺 Multiple Disease Prediction Tool (MDPT)
Welcome to MDPT (Multiple Disease Prediction Tool) — a machine learning-based web application that predicts the likelihood of multiple diseases based on user input. This project combines data science, frontend development, and healthcare insights to create an easy-to-use tool for early disease risk detection.

📚 Project Overview
MDPT is designed to predict the risk of diseases like:

Diabetes

Heart Disease

Parkinson’s Disease

Breast Cancer

It uses trained machine learning models on relevant healthcare datasets and provides a simple and responsive frontend for users to input their health parameters and get instant predictions.

🛠️ Tech Stack
Area	Tools Used
Frontend	HTML, Tailwind CSS, JavaScript
Backend	Python (Flask Framework)
Machine Learning	Scikit-learn, Pandas, Numpy
Deployment	GitHub Pages / Localhost
🔥 Features
Predict multiple diseases from a single platform

Responsive and clean user interface

Trained and optimized machine learning models

User-friendly health parameter input forms

Quick and reliable predictions

Mobile and desktop compatible

🧠 MDPT Analysis
During the development of MDPT, we performed an in-depth analysis to ensure the tool's reliability and performance:

Data Preparation: Cleaned and preprocessed medical datasets for each disease separately.

Model Selection: Used various algorithms like Logistic Regression, Random Forest, SVM, and Decision Trees.

Model Evaluation: Models were evaluated using metrics like accuracy, precision, recall, and F1-score. The best-performing models were selected.

Optimization: Hyperparameter tuning was performed to enhance the prediction accuracy.

Result: Achieved a consistent accuracy score of 85%+ across different disease datasets.

Frontend-Backend Integration: Ensured smooth data flow between user input and model prediction output.

UI/UX Testing: Iterated the design with different color schemes (finalized Red + White theme) to make it visually appealing and easy to use.

The MDPT project demonstrates how machine learning can be effectively combined with intuitive web design to make complex medical predictions accessible to everyone.

🚀 How to Run Locally
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/MDPT.git
cd MDPT
Install required Python packages:

bash
Copy
Edit
pip install -r requirements.txt
Run the Flask app:

bash
Copy
Edit
python app.py
Open your browser and navigate to:

arduino
Copy
Edit
http://localhost:5000
🧩 Folder Structure
cpp
Copy
Edit
MDPT/
│
├── static/
│   └── styles.css (Tailwind CSS styles)
├── templates/
│   ├── index.html
│   ├── result.html
├── models/
│   ├── diabetes_model.pkl
│   ├── heart_model.pkl
│   ├── parkinson_model.pkl
│   └── breast_cancer_model.pkl
├── app.py
├── requirements.txt
└── README.md
✨ Future Improvements
Add more disease predictions

Integrate deep learning models for higher accuracy

Add user authentication for personalized reports

Deploy on cloud platforms like Heroku or AWS

🙌 Acknowledgements
Healthcare datasets sourced from trusted repositories like Kaggle and UCI Machine Learning Repository.

Special thanks to open-source contributors and healthcare researchers.

📫 Contact
For feedback or collaboration:

Adarsh Shameekapoor Kamde

LinkedIn | GitHub

MDPT — Predict Smart, Live Healthier! 🚀

Link - https://ak-insane07.github.io/MDPT_majorProject/



