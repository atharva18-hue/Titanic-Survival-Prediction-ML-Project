\# 🚢 Titanic Survival Prediction ML Project



Predicting passenger survival on the Titanic using \*\*Machine Learning\*\* 🧠💻.  

This Django-based web application integrates predictive models, interactive templates, and a user-friendly interface to explore survival predictions. 📊✨



----------------------------------------------------------------



\## 🔹 Features

\- Clean and preprocess Titanic dataset 🧹

\- Feature engineering for better model performance ⚙️

\- Machine Learning models: Logistic Regression, Random Forest, Decision Trees 🌳🤖

\- Interactive web interface with Django templates 🖥️

\- Predict survival for new passengers in real-time 🛳️

\- Results displayed clearly with HTML pages 🏆



----------------------------------------------------------------



\## 🛠️ Tech Stack

\- \*\*Backend:\*\* Python, Django 🐍

\- \*\*Data Processing:\*\* Pandas, NumPy 📊

\- \*\*Machine Learning:\*\* Scikit-learn 🤖

\- \*\*Frontend:\*\* HTML, CSS, Bootstrap 🎨

\- \*\*Model Storage:\*\* Joblib `.joblib` files 💾



----------------------------------------------------------------



\## ⚡ Setup Instructions



\# 1. Clone the repository

git clone https://github.com/atharva18-hue/Titanic-Survival-Prediction-ML-Project.git

cd Titanic-Survival-Prediction-ML-Project



----------------------------------------------------------------



\# 2. Create a virtual environment

python -m venv venv

.\\venv\\Scripts\\activate   # Windows



----------------------------------------------------------------



\# 3. Install dependencies

pip install -r requirements.txt



----------------------------------------------------------------



\# 4. Apply migrations

python manage.py migrate



----------------------------------------------------------------



\# 5. Run development server

python manage.py runserver



----------------------------------------------------------------



\# 6. Open in browser

http://127.0.0.1:8000/



----------------------------------------------------------------



📂 Project Structure



Titanic-Survival-Prediction-ML-Project/

&nbsp;├── manage.py

&nbsp;├── db.sqlite3

&nbsp;├── static/                # CSS, JS, images, GIFs

&nbsp;├── templates/             # HTML pages (home, result, error)

&nbsp;├── webMLModel/            # Django project core

&nbsp;│    ├── \_\_init\_\_.py

&nbsp;│    ├── settings.py

&nbsp;│    ├── urls.py

&nbsp;│    ├── views.py

&nbsp;│    ├── wsgi.py

&nbsp;│    ├── asgi.py

&nbsp;│    ├── SurvivalPrediction-model.joblib

&nbsp;│    └── titanic.csv

&nbsp;├── venv/                  # Ignored in git

&nbsp;├── .gitignore

&nbsp;└── README.md



----------------------------------------------------------------



🎯 Usage

Open the web application



Fill passenger details



Click Predict



View survival prediction results 🏆



----------------------------------------------------------------



🤝 Contributing

Pull requests are welcome!



Improve ML model accuracy



Enhance UI/UX



Add new features



----------------------------------------------------------------



📌 Notes

This is a development server only ⚠️



Keep .env for secret keys 🔒



Joblib model files are already included for prediction 💾



----------------------------------------------------------------

