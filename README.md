This project explores a machine learning-based approach to diabetes prediction by integrating multiple patient data points (such as age, BMI, blood pressure, etc.) with medical history. The system aims to:
develop a machine learning model that can analyze patient data, such as age, BMI, blood pressure, and other relevant features, to predict the likelihood of a person developing diabetes
to provide a tool for early intervention, helping healthcare professionals identify high-risk individuals and offer personalized recommendations to manage or prevent the disease
Django was used in PyCharm to develop a dynamic web application for diabetes prediction.
HTML templates (home.html and predict.html) were created to design the user interface for data input and displaying results.
In views.py, the Logistic Regression model was integrated directly without pickling. The dataset was loaded, preprocessed, and trained in real-time upon user request
User-provided health metrics were collected through a web form and passed to the model for prediction.
The trained model predicted whether the user is Diabetic or Non-Diabetic, and the result was dynamically displayed on the website.
