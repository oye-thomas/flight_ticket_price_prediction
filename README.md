✈️ Flight Price Prediction

End-to-End Machine Learning | Statistical Analysis | Streamlit

Project Overview

An end-to-end machine learning project focused on predicting airline ticket prices using flight-related features.

The project combines exploratory data analysis, statistical hypothesis testing, supervised learning, and uncertainty estimation to build a predictive solution, deployed through an interactive Streamlit application.

Key Highlights

* EDA & Statistical Analysis: Explored 300,000+ observations, identified relevant patterns, and conducted statistical hypothesis testing.
* Machine Learning: Developed, trained, and optimized a regression model for flight price prediction.
* Model Evaluation: Assessed predictive performance using MAE, RMSE, and R².
* Uncertainty Estimation: Applied the Central Limit Theorem to construct a 95% confidence interval around the test MAE.
* Deployment: Built an interactive Streamlit application to generate flight price estimates.

Model Performance

Metric	Test Score
MAE	1,105.26
RMSE	2,794.89
R²	0.9848

The model explains approximately 98.48% of the variance in ticket prices on the test dataset.

Tech Stack

Python · Pandas · NumPy · SciPy · Scikit-learn · Matplotlib · Seaborn · Plotly · Streamlit · Poetry · Git

Run Locally

git clone https://github.com/oye-thomas/flight_ticket_price_prediction.git
cd prediction_de_prix_de_billet
poetry install
poetry run streamlit run dashboard.py

Future Improvements

* Model explainability and feature importance.
* Docker containerization and cloud deployment.

Author

Thomas Alaby | Machine Learning & Data Science

GitHub Profile :https://github.com/oye-thomas