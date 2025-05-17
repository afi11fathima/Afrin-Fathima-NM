# AQI Predictor Backend

This is the backend service for the AQI Predictor project. It handles data processing, model training, and prediction APIs.

## Features

- Machine Learning model to predict Air Quality Index (AQI)
- Flask API for serving predictions
- Preprocessing of environmental datasets

## Installation

```bash
cd aqi-predictor-backend
pip install -r requirements.txt
python app.py
```

## API Endpoints

- `/predict`: Accepts environmental features and returns predicted AQI level

## Folder Structure

```
aqi-predictor-backend/
├── app.py
├── model.pkl
├── requirements.txt
└── README.md
```