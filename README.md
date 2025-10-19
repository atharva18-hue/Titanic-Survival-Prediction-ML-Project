#  Titanic Survival Prediction ML Project



 Predicting passenger survival on the Titanic using **Machine Learning**  
A Django web app integrating predictive models, interactive templates, and a user-friendly interface. 

---

## Project Video

https://github.com/user-attachments/assets/35f1c4f7-831b-4a0d-990f-8203c7900ff4

----------------------------------------------------------------

##  Features
- Clean and preprocess Titanic dataset  
-  Feature engineering for better model performance  
- Machine Learning models: Logistic Regression, Random Forest, Decision Trees  
- Interactive web interface with Django templates  
-  Predict survival for new passengers in real-time  
- Results displayed clearly with HTML pages  

---

## Tech Stack
- **Backend:** Python, Django 
- **Data Processing:** Pandas, NumPy 
- **Machine Learning:** Scikit-learn   
- **Frontend:** HTML, CSS, Bootstrap   
- **Model Storage:** Joblib `.joblib` files  

------------------------------------------------------------------------------------------------

##  Setup Instructions

# Clone repository
git clone https://github.com/atharva18-hue/Titanic-Survival-Prediction-ML-Project.git
cd Titanic-Survival-Prediction-ML-Project

------------------------------------------------------------------------------------------------

# Create virtual environment
python -m venv venv
.\venv\Scripts\activate

------------------------------------------------------------------------------------------------

# Install dependencies
pip install -r requirements.txt

------------------------------------------------------------------------------------------------

# Apply migrations
python manage.py migrate

------------------------------------------------------------------------------------------------

# Run server
python manage.py runserver

------------------------------------------------------------------------------------------------

# Open in browser
http://127.0.0.1:8000/

------------------------------------------------------------------------------------------------

 ## Project Structure
 
Titanic-Survival-Prediction-ML-Project/
 ├── manage.py
 ├── db.sqlite3
 ├── static/        # CSS, JS, images, GIFs
 ├── templates/     # HTML pages
 ├── webMLModel/    # Django core
 │    ├── __init__.py
 │    ├── settings.py
 │    ├── urls.py
 │    ├── views.py
 │    ├── wsgi.py
 │    ├── asgi.py
 │    ├── SurvivalPrediction-model.joblib
 │    └── titanic.csv
 ├── venv/          # Ignored in git
 ├── .gitignore
 └── README.md

 ----------------------------------------------------------------------------------------------
 
 ## Usage Flow:

Open the web application in a browser

Fill passenger details (age, sex, class, etc.)

Click Predict

View survival prediction results

-----------------------------------------------------------------------------------------------

## Highlights:

Fully functional Django + ML web app

Real-time predictions using pre-trained ML models

Clean, interactive UI for easy testing

------------------------------------------------------------------------------------------------

## Notes

 Development server only

 Keep .env for secret keys

 Joblib model files included

------------------------------------------------------------------------------------------------

##  Author
**Atharva Chavhan**  
- GitHub: [atharva18-hue](https://github.com/atharva18-hue)  
- Email: atharvachavhan18@gmail.com

- ----------------------------------------------------------------------------------------------
