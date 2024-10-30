# Breast Cancer Prediction

This repository contains a machine learning project focused on predicting breast cancer diagnoses. The project includes data analysis, model training, and a web application built using Flask to make predictions on new data inputs.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Installation](#installation)
4. [Usage](#usage)
5. [File Descriptions](#file-descriptions)
6. [Model Details](#model-details)
7. [Future Work](#future-work)
8. [Contributing](#contributing)
9. [License](#license)

## Project Overview
The goal of this project is to build a predictive model to classify breast cancer as either malignant or benign based on medical data. The machine learning model has been integrated into a Flask web application to allow users to interact with the model through a user-friendly interface.

## Dataset
The dataset used in this project is saved as `BreastCancerData.csv`. It includes features related to cell nuclei characteristics, which are used to train the model to predict the diagnosis.

## Installation
To run this project locally, please follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/kabirkohli123/BreastCancerPredictionApp.git
   cd BreastCancerPredictionApp
   ```

2. Create a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Flask app:
   ```bash
   python app.py
   ```

The application will start on `http://127.0.0.1:5000/` by default.

## Usage
To use the app:
1. Open the application in a web browser.
2. Enter the relevant features in the provided form.
3. Submit the form to receive a prediction.

## File Descriptions
- `BreastCancerData.csv`: Contains the dataset used for training and testing.
- `BreastCancerApp.ipynb`: Jupyter notebook with data analysis, model training, and evaluation.
- `app.py`: Flask application file that serves the web app and handles prediction requests.

## Model Details
The machine learning model used in this project is trained on features that include cell nucleus characteristics. Common algorithms used for such tasks include logistic regression, support vector machines, and decision trees. Please refer to `BreastCancerApp.ipynb` for details on model training and evaluation.

## Future Work
- Enhancements to the user interface for better user experience.
- Deployment to a cloud platform for remote access.
- Exploring additional features or models to improve prediction accuracy.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions.

## License
This project is licensed under the MIT License.
