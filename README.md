# Forest Fire Prediction using Algerian Forest Fire Data

This project aims to predict forest fires using machine learning techniques applied to the Algerian Forest Fire dataset. The project involves data preprocessing, exploratory data analysis (EDA), model building, and evaluation.

## Dataset

The dataset contains meteorological data and fire occurrence information from two regions in Algeria: the Bejaia region and the Sidi Bel-abbes region. The data covers the period from June 2012 to September 2012 and includes variables such as temperature, relative humidity, wind speed, and rain.

## Project Structure

- `data/`: Contains the dataset files.
- `notebooks/`: Jupyter notebooks for EDA and model building.
- `src/`: Source code for data processing, feature engineering, and model training.
- `models/`: Saved machine learning models.
- `README.md`: Project overview and instructions.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in `requirements.txt`)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/Arpan2307/Forest_Fire_EDA_Regressor_Model
    cd Forest_Fire_EDA_Regressor_Model
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

### Dataset

The dataset is available in the `dataset/` directory. If not present, you can download it from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Algerian+Forest+Fires+Dataset).

### Usage

1. Perform Exploratory Data Analysis (EDA) using the provided Jupyter notebook:
    ```sh
    jupyter notebook NOTEBOOKS/EDA_Forest_Fire.ipynb
    ```

2. Train the machine learning model using the provided notebook or source code:
    ```sh
    jupyter notebook notebooks/Model_Training.ipynb
    ```

3. Evaluate the model and make predictions:
    ```sh
    run the app2.py file to use the web app
    ```

## Exploratory Data Analysis (EDA)

EDA is a critical step in understanding the dataset and identifying patterns, anomalies, and relationships between variables. In this project, EDA includes:

- Data Cleaning: Handling missing values, outliers, and inconsistencies.
- Data Visualization: Plotting distributions, correlations, and trends.
- Feature Engineering: Creating new features and selecting relevant ones.
- Statistical Analysis: Summarizing and interpreting data characteristics.

## Machine Learning Models

Several machine learning models are implemented and evaluated in this project, including:

- Multiple Linear Regression
- Lasso Regression
- Ridge Regression
- Elastic Net Regression


Model performance is assessed using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R²).


## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

## Acknowledgements

- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php) for providing the dataset.
- Contributors and maintainers of open-source libraries used in this project.
