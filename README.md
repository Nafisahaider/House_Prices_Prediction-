# House_Prices_Prediction-
Regression Model to predict the price of the house based on their square footage and the no of bedroom and bathroom
House Price Prediction

This project predicts house prices based on features such as area, number of bedrooms, and bathrooms. The model uses a machine learning approach, leveraging the power of linear regression.

## Features

Data Processing: Loading and preprocessing a dataset of housing features.

Model Training: Linear regression to predict house prices.

Evaluation: Metrics such as Mean Squared Error (MSE) and R-squared are used to evaluate model performance.

## Installation

### To run this project:

Python 3.x

Jupyter Notebook

### Install the required Python libraries:

pip install numpy pandas scikit-learn matplotlib

## Usage

### Clone this repository:

git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

### Open the Jupyter Notebook:

jupyter notebook House_price.ipynb

Run the notebook cells sequentially to load the data, train the model, and evaluate the performance.

## Dataset

### The project uses a CSV dataset with the following columns:

price: Target variable (house price).

area: Square footage of the house.

bedrooms: Number of bedrooms.

bathrooms: Number of bathrooms.

Additional columns include features like parking availability, guestroom, and furnishing status.

df= pd.read_csv('/content/drive/My Drive/data/Housing.csv')

## Key Components

Preprocessing: Checking for null values and normalizing data.

Feature Selection: Selecting features such as area, bedrooms, and bathrooms for prediction.

Model Training: Splitting the data into training and testing sets and fitting a linear regression model.

Evaluation: Calculating MSE and R-squared to measure model accuracy.

## Results

The notebook demonstrates step-by-step predictions and evaluates the model's performance using various metrics. Visualizations are included to show the relationship between features and the target variable.

## Contributing

Contributions are welcome! If you have suggestions or improvements, feel free to open an issue or submit a pull request.
