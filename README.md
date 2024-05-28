# Random Forest for XSS and SQL Injection Detection

This repository contains the implementation of Random Forest classifier for XSS and SQL injection detection, along with an LSTM model for validating the results based on the provided dataset.

## Files

### Jupyter Notebooks

- **RandomForest_XSS_and_SQL.ipynb**: This notebook contains the code implementation of the Random Forest classifier for detecting XSS and SQL injection attacks. It includes data preprocessing, model training, evaluation, and visualization of results.

- **LSTM_model_for_XSS_and_SQL_injection.ipynb**: This notebook implements an LSTM model for validating the results based on the dataset provided.

### Dataset

- **bad.csv**: Dataset containing instances labeled as 'bad', representing XSS and SQL injection attacks.

- **good.csv**: Dataset containing instances labeled as 'good', representing legitimate data.

## Usage

To run the code and reproduce the results:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/AliRazaLilani/RandomForest-Thesis.git
2. Open the Jupyter notebooks (`RandomForest_XSS_and_SQL.ipynb` and `LSTM_model_for_XSS_and_SQL_injection.ipynb`) in a Jupyter Notebook environment or any compatible platform.

3. Execute the code cells in the notebooks sequentially to preprocess the data, train the models, and evaluate the results.

## Dependencies

The implementation relies on the following Python libraries:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tensorflow (for LSTM model)

You can install the dependencies using pip:
 ```bash
   pip install pandas numpy scikit-learn matplotlib seaborn tensorflow
