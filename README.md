# Heart Disease Prediction System

A modern, machine-learning-powered web application built with Django that predicts the likelihood of heart disease based on patient medical profiles. The system is designed to provide quick, accessible, and intelligent medical decision support.

## 🚀 Key Features

* **Modernized for Django 6.0**: Fully updated and compatible with the latest Django releases.
* **Intelligent Prediction System**: Leverages Machine Learning models (Gradient Boosting & Logistic Regression) to assess heart disease risk using 13 key medical parameters (age, sex, cholesterol, blood pressure, ECG results, etc.).
* **Brand New Patient Dashboard**: A completely redesigned, sleek CSS-grid interface that offers quick access to prediction tools, history, profiles, and feedback mechanisms.
* **Intuitive Medical Forms**: Re-engineered prediction forms featuring user-friendly dropdowns, clear medical parameter helpers, and a responsive layout that replaces cramped horizontal inputs.
* **Role-Based Access**: Specialized portals for Patients, Doctors, and Administrators.
* **History & Tracking**: Keeps a historical record of prediction results for patients.
* **Doctor Locality Recommendations**: Suggests appropriate doctors based on the prediction results.

## 🛠️ Technology Stack

**Frontend:**
* HTML5 / CSS3
* Vanilla JavaScript
* Bootstrap 5
* FontAwesome Icons

**Backend:**
* Python 3.10+
* Django 6.0+
* SQLite (Database)

**Machine Learning / Data Science:**
* NumPy
* Pandas
* Scikit-Learn
* UCI Heart Disease Dataset

## 📦 Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/shambhavikumari088-source/Heart-Disease-Prediction-System.git
   cd Heart-Disease-Prediction-System
   ```

2. **Create a virtual environment (Recommended)**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Database Migrations**
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```

5. **Start the Development Server**
   ```bash
   python manage.py runserver
   ```
   Navigate to `http://127.0.0.1:8000/` in your browser.

## 👥 User Roles & Modules

* **Patients**: Can register, log in, manage their profile, submit medical data for instant prediction, view prediction history, and search for doctors.
* **Doctors**: Can log in, manage their profile, and view patient details.
* **Admin**: Has full access to manage doctors, view all patient histories, manage diseases, upload new datasets, and review system feedback.

## 🔮 Future Scope
* Integration with live hospital databases.
* Continuous model retraining using newly collected patient data.
* Advanced Deep Learning model integration for higher accuracy.

## 📄 License
This project is open-source and available under the [MIT License](LICENSE).
