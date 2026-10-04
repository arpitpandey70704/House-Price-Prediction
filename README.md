# House Price Prediction

🌐 **Live Demo:** https://house-price-prediction-5qbkkymvarhabavcrms8n3.streamlit.app/

An application that predicts the estimated price of a house based on its property details.

## Project Description

This project uses Machine Learning to predict house prices based on different property features such as:

* Area
* Number of bedrooms
* City
* Location
* Car parking
* Swimming pool
* 24x7 security
* Lift availability
* Clubhouse

The trained Machine Learning model is integrated with a Streamlit web application, where users can enter property details and get an estimated house price.

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib
* Streamlit
* Jupyter Notebook

## Project Files

* `app.py` – Streamlit web application
* `data.csv` – Dataset used for the project
* `final_data.csv` – Cleaned and processed dataset
* `index.ipynb` – Jupyter Notebook containing data analysis, preprocessing and model training
* `index.txt` – Notes and dataset analysis
* `city_encoder.joblib` – Encoder for city data
* `location_encoder.joblib` – Encoder for location data
* `model.joblib` – Trained Machine Learning model
* `requirements.txt` – Required Python libraries

## How to Run

Install the required libraries using:

```bash
pip install -r requirements.txt
```

Then run the Streamlit application:

```bash
streamlit run app.py
```

The application will open in the browser and allow the user to enter property details and receive an estimated house price.
