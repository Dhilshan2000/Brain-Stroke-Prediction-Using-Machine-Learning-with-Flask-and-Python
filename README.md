# Brain-Stroke-Prediction-Using-Machine-Learning-with-Flask-and-Python


This project is a Flask-based web application designed to predict the likelihood of a stroke in individuals using machine learning. The model uses various health-related inputs such as age, gender, blood glucose level, BMI, and lifestyle factors like smoking status and work type to predict stroke risk.

**Features**

Web Interface: A user-friendly form where users can input their health-related details.

Prediction Model: A machine learning model that predicts the likelihood of a stroke based on user input.

Prediction Result: Displays whether the user is "Likely" or "Not Likely" to have a stroke.

**Technologies Used**

Flask: Web framework used for creating the web application.

Bootstrap: Frontend framework for responsive design.

Pandas: Data manipulation library used for handling input data.

Joblib: Library used for loading the pre-trained machine learning model.

HTML/CSS: For the structure and styling of the web pages.

**How it Works**

**Frontend**

The frontend consists of HTML forms where users can input their health details, including:

Age
Gender
Hypertension status
Heart disease status
Glucose levels
BMI
Smoking status
Work type
Residence type
Ever married status

**Backend**

When the user submits the form, the backend processes the input and predicts the likelihood of a stroke based on a pre-trained model. The model was trained using historical health data and includes features like age, hypertension, and glucose levels. The prediction is then displayed on a result page.

**Model**

The model is stored in model.joblib, and it is loaded using Joblib for making predictions based on the input provided by the user.

![Application Screenshot]("D:\OneDrive - National Institute of Business Management\Certificates\Projects\ML Projects\Brain Stroke Prediction Using Machine Learning with Flask and Python\WebApp.jpg")
