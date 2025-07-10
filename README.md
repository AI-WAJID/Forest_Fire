# Algerian Forest Fire FWI Prediction

This project predicts the Fire Weather Index (FWI) for Algerian forests using a machine learning model. It includes a Flask web application for user interaction and model inference.

# Live server link : https://forest-fire-ydrp.on
# you can access it through this link https://forest-fire-ydrp.onrender.com/predictdata

## Project Structure

```
workspace/
│
├── application.py
├── models/
│   ├── ridge.pkl
│   └── scaler.pkl
├── notebook/
│   ├── Algerian_forest_fires_clean_dataset.csv
│   ├── ModelTraining.ipynb
│   └── ridge_lasso_regression.ipynb
└── templates/
    ├── home.html
    └── index.html
```

## Features

- **Web Interface:** Enter weather parameters and get FWI predictions.
- **Pre-trained Model:** Uses Ridge Regression and Standard Scaler.
- **Jupyter Notebooks:** For data analysis and model training.

## Getting Started

### Prerequisites

- Python 3.7+
- pip

### Install Dependencies

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, install manually:

```bash
pip install flask pandas numpy scikit-learn
```

### Running the App

1. Navigate to the `workspace` directory:
    ```bash
    cd workspace
    ```

2. Start the Flask app:
    ```bash
    python application.py
    ```

3. Open your browser and go to [http://localhost:5000](http://localhost:5000).

## Usage

- Fill in the weather parameters on the home page.
- Click **Predict** to get the FWI prediction.

## Files

- `application.py`: Main Flask application.
- `models/`: Contains the trained model and scaler.
- `notebook/`: Data and Jupyter notebooks for training and analysis.
- `templates/`: HTML templates for the web interface.

## License

This project is for educational purposes.

---

**Author:** AI-WAJID  
**Contact:**
