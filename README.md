# Project-10-Intensity-Analysis# Intensity Analysis Model Deployment

## Overview
This project uses NLP and machine learning to classify text into three intensity categories: happiness, angriness, or sadness. The trained model is deployed using Flask for real-time predictions.

## Installation
### Prerequisites
Ensure you have Python 3.7+ installed along with the following dependencies:
```bash
pip install flask pandas numpy joblib scikit-learn
```

## Model Files
- `intensity_model.pkl`: Trained ML model for classification.
- `tfidf_vectorizer.pkl`: TF-IDF vectorizer used for text transformation.

## Running the API
To start the Flask server, run:
```bash
python app.py
```
By default, the API will be available at `http://127.0.0.1:5000/`.

## API Usage
### Endpoint: `/predict`
**Method:** `POST`

**Request Format:**
```json
{
    "text": "This is an example text."
}
```

**Response Format:**
```json
{
    "prediction": "happiness"
}
```

## Future Improvements
- Expand dataset for better model generalization.
- Deploy on cloud services like AWS, GCP, or Heroku.
- Build a web UI for user interaction.

## Author
Krishnapriya Adepu


