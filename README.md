# Restaurant Cuisine Classification Using Machine Learning

## 1. Project Overview
This project predicts a restaurant's cuisine category using machine learning based on restaurant details such as rating, votes, approximate cost, restaurant type, ordering options, and location.

## 2. Objectives
- Inspect and clean restaurant data.
- Prepare training and testing datasets.
- Train and compare classification models.
- Evaluate model performance.
- Predict cuisine categories for restaurant inputs.

## 3. Technologies Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Joblib
- Visual Studio Code

## 4. Machine Learning Algorithms
1. Logistic Regression
2. Random Forest Classifier

## 5. Model Results
- Logistic Regression accuracy: approximately 21.36%.
- Random Forest accuracy: approximately 39.61%.

Random Forest performed better on the test dataset in this experiment. Performance varies by cuisine category, and some categories have very few examples.

## 6. Main Project Files
- `01_check_dataset.py` — inspect the dataset
- `02_data_preprocessing.py` — clean the data
- `03_prepare_data.py` — prepare training and testing data
- `04_train_models.py` — train and compare models
- `05_analyze_results.py` — evaluate results and generate charts
- `06_save_model.py` — save the trained model
- `07_predict_cuisine.py` — make a sample prediction
- `08_interactive_predict.py` — predict using entered restaurant details
- `cuisine_model.joblib` — saved machine-learning model

## 7. How to Run
1. Install Python.
2. Open the project folder in VS Code.
3. Install the dependencies with `python -m pip install -r requirements.txt`.
4. Run `python 08_interactive_predict.py`.

The saved model file must be present to run predictions.

## 8. Limitations
The model does not always predict cuisine correctly. Its accuracy is limited by the dataset, overlapping restaurant characteristics, and the number of examples available for each cuisine.

## 9. Future Improvements
- Improve performance on underrepresented cuisines.
- Tune model parameters.
- Evaluate additional algorithms.
- Build a simple web interface.
- Test on new restaurant data.