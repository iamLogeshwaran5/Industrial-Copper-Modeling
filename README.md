# Industrial Copper Modeling Application

This Streamlit application provides functionalities for predicting selling prices and statuses for industrial copper modeling.

## Introduction

The Industrial Copper Modeling Application offers predictive analysis tools for industrial workforce distribution. Users can predict selling prices and statuses based on input parameters.

## Features

- **Predict Selling Price**: Users can input parameters such as status, item type, country, application, product reference, quantity tons, thickness, width, and customer ID to predict selling prices.
- **Predict Status**: Users can input parameters such as quantity tons, thickness, width, customer ID, selling price, item type, country, application, and product reference to predict the status.

## Data Preprocessing and Analysis

The application preprocesses the dataset and performs analysis before model training. It includes the following steps:
- Handling missing values and incorrect data formats
- Data visualization and analysis
- Decision Tree Regressor and Decision Tree Classifier models for prediction

## Usage

1. Run the application using Streamlit.
2. Navigate through different tabs to access prediction functionalities.
3. Input the required parameters and click on the corresponding button to generate predictions.

## Installation

1. Clone the repository: `git clone https://github.com/yourusername/industrial-copper-modeling.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the application: `streamlit run main.py`

## Dependencies

- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib
- streamlit

## File Structure

The project files are organized as follows:
- `main.py`: Main script for running the Streamlit application.
- `Dataset/`: Directory containing the dataset (e.g., `Copper_set.csv`).
- `source/`: Directory containing the model files (e.g., `model.pkl`, `scaler.pkl`, `t.pkl`, `s.pkl`, `cmodel.pkl`, `cscaler.pkl`, `ct.pkl`).

## Author

- **LOGESHWARAN**
- LinkedIn: [LOGESHWARAN's LinkedIn Profile](https://www.linkedin.com/in/logeshwarandatapro/)

## Contact

For any inquiries or feedback, please contact LOGESHWARAN at logeshwaran1478@gmail.com.
