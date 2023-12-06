# Sales Prediction Using LSTM

This repository contains code for predicting sales using LSTM (Long Short-Term Memory) neural networks based on historical sales data for multiple items in different stores.

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [File Structure](#file-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on predicting sales for multiple items across different stores using LSTM models. It utilizes historical sales data to forecast sales for future time periods.

## Dataset

The dataset used in this project comprises historical sales data for multiple items across different stores. The dataset includes features like date, store ID, item ID, and sales figures.

**Columns:**
- `date`: Date of the sales record
- `store`: Store ID
- `item`: Item ID
- `sales`: Sales figures

## Usage

To use this project:
1. Clone the repository: `git clone https://github.com/abhi7275/sales-prediction-lstm.git`
2. Install the necessary dependencies: `pip install -r requirements.txt`
3. Run the main script: `python sales_prediction.py`

## Dependencies

- Python 3.x
- Pandas
- NumPy
- Keras
- Scikit-learn

## File Structure

- `README.md`: Information about the project
- `sales_prediction.py`: Main script for sales prediction using LSTM
- `train_dataset.csv`: Training dataset containing historical sales data
- `test_dataset.csv`: Test dataset for predicting future sales
- `predicted_sales.csv`: Output file containing predicted sales
- `requirements.txt`: List of dependencies

## Results

The model trained on the historical sales data successfully predicts sales for future time periods. Results and visualizations are available in the `predicted_sales.csv` file and in the notebook `sales_prediction.ipynb`.

## Contributing

Contributions are welcome! Feel free to submit issues and enhancement requests. Please follow the contribution guidelines before submitting pull requests.

## License

This project is licensed under the [MIT License](LICENSE).

