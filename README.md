# Airbnb New User Booking Prediction

This repository contains the code and resources for predicting the country destination of new users on Airbnb. The project uses machine learning techniques to build a model that predicts the country where a new user will make their first travel booking.

## Dataset

The dataset used for this project is the "Airbnb New User Bookings" dataset obtained from the Kaggle competition hosted by Airbnb. It includes various user features such as age, gender, signup method, and more, along with the target variable "country_destination."

## Approach

The goal of this project is to predict a categorical target variable ("country_destination") based on user features. Here's an overview of the approach:

1. Data Preprocessing: Load, clean, and preprocess the dataset. Handle missing values and convert categorical variables into numerical format.

2. Feature Engineering: Extract relevant features from the dataset, such as age and gender.

3. Model Selection: Since the target variable is categorical, we use classification algorithms such as Random Forest Classifier.

4. Model Training: Train the chosen classification algorithm on the preprocessed data.

5. Model Evaluation: Evaluate the model's performance using classification metrics like accuracy, precision, recall, and F1-score.

6. Prediction and Submission: Use the trained model to predict the country destinations for new users in the test dataset and prepare a submission file.

## Files and Directories

- `data/`: Directory containing the dataset files.
- `notebooks/`: Jupyter notebooks for data exploration, preprocessing, and modeling.
- `models/`: Trained model files.
- `src/`: Source code for preprocessing, modeling, and evaluation.
- `README.md`: This file providing an overview of the project.

## Requirements

- Python 3.x
- Required libraries are listed in `requirements.txt`.

## Getting Started

1. Clone this repository.
2. Install the required libraries using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks in the `notebooks/` directory for data exploration, preprocessing, and modeling.
4. Train and evaluate the model using the provided source code in the `src/` directory.
5. Make predictions for the test dataset and prepare a submission file.

## Results

Document the results of your model, including evaluation metrics and any insights gained from the analysis.

## Challenges and Future Work

Discuss any challenges faced during the project and potential areas for improvement in the future.

## License

This project is licensed under the [MIT License](LICENSE).

Feel free to contact me at [your@email.com] for any questions or collaborations.
