# 🧠 Diabetes Prediction Web App

A full-stack machine learning web application built using **Django** to predict the likelihood of diabetes in a patient based on medical inputs such as glucose level, BMI, age, and more. The model is trained on the **Pima Indians Diabetes dataset** and deployed on **Render**.

🔗 **Live App**: [https://diabetes-pred-e95t.onrender.com](https://diabetes-pred-e95t.onrender.com)

---

## 🚀 Features

- ✅ Real-time diabetes prediction using an ML model
- ✅ Django-powered backend with form-based UI
- ✅ Trained model using Logistic Regression
- ✅ Deployed on Render with Gunicorn
- ✅ Clean medical input form interface

---

## 📁 Project Structure
```plaintext
DiabetesPrediction/ # Django project folder
├── init.py
├── asgi.py
├── settings.py
├── urls.py
├── views.py # Optional: root-level views
├── wsgi.py

predictor/ # Django app
├── init.py
├── admin.py
├── apps.py
├── forms.py
├── migrations/
│ └── init.py
├── models.py
├── templates/
│ └── predictor/
│ └── predict.html
├── tests.py
├── views.py

model/
└── diabetes_model.pkl # Trained ML model (pickle format)
```

---

## 🧠 ML Model

- **Dataset**: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Algorithm**: **Logistic Regression**
- **Libraries Used**:
  - `scikit-learn`
  - `pandas`
  - `numpy`
  - `pickle`

---

## 🌐 Deployment Notes

- Hosted on: [Render](https://render.com)
- Web process defined via: `Procfile`
- Production server: `gunicorn`
- `ALLOWED_HOSTS` includes the Render domain
- Model file: `diabetes_model.pkl` must be present in the `/model` directory

---

## 🧪 Usage

1. Go to the deployed link
2. Enter user medical data in the form
3. Submit and receive an immediate prediction:
   - **Diabetic**
   - **Not Diabetic**

---

## 📸 Screenshots
![image](https://github.com/user-attachments/assets/42ea9bb9-2325-4e84-8037-5c1a824c7811)

| Input Form | Prediction Result |
|------------|-------------------|
| ![image](https://github.com/user-attachments/assets/6776bca2-9db4-496f-8373-76c3623a61d3)|![image](https://github.com/user-attachments/assets/eaeddef0-2cd0-4c48-afc2-b97edb523089)
|




---

Let me know if you'd like this exported as a `.md` file or auto-added to your project repo!

