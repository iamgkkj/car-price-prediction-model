# Car Price Prediction App - Project Context

## Project Overview
Machine Learning web application that predicts car resale prices using a Random Forest Regressor model deployed on Flask.

## Tech Stack
- **Backend**: Flask, Python 3.10
- **ML**: Scikit-learn, Pandas, NumPy
- **Frontend**: HTML, CSS with Orbitron font
- **Deployment**: Render (cloud platform)

## Project Structure
```
car-price-prediction-app/
├── static/
│   ├── style.css          # Custom UI styling with green theme
│   └── image.png          # Background image
├── templates/
│   └── index.html         # Main frontend form
├── app.py                 # Flask application
├── car_price_model.pkl    # Serialized ML model
├── requirements.txt       # Dependencies
└── Procfile              # Production config
```

## Recent Changes (July 1, 2026)
- Updated UI with robotic Orbitron font
- Applied green accent color scheme with gradients
- Made UI rounded with increased border-radius (12-24px)
- Added transparency effects with rgba backgrounds
- Implemented blurred background using image.png
- Added "made by gopal" footer with GitHub icon linking to https://github.com/iamgkkj/car-price-prediction-model
- No "Akshat" references found in frontend (only in README.md documentation)

## Features
- Real-time car price prediction
- Input fields: Present Price, Kilometers Driven, Fuel Type, Seller Type, Transmission, Owners, Car Age
- Responsive design with modern UI
