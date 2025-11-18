# Crop Prediction using Machine Learning

This project predicts which crop is most suitable based on soil nutrients and weather conditions (N, P, K, temperature, humidity, pH, rainfall).

## Models Used
- OVR Classifier
- SVM
- Random Forest (final model)

After comparing all models using accuracy, F1-score and confusion matrix, Random Forest performed best and was used for the final prediction model.

## Streamlit App
I created a Streamlit interface to input soil and environmental values and get crop prediction.

To run:
pip install -r requirements.txt  
streamlit run app.py

## Files
- app.py – Streamlit interface  
- crop_prediction_model.pkl – Trained model  
- requirements.txt – Dependencies  

