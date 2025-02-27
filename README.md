# USA Household Price Prediction using Linear Regression

## Overview
This project uses a linear regression model to predict housing prices in the United States, based on factors like average area income, house age, and population. The dataset includes various features that influence housing prices, enabling analysis and prediction through data processing and visualization techniques.

## Table of Contents
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Dataset
The dataset `USA_Housing.csv` contains 5000 entries with the following columns:
- **Avg. Area Income**: Average income of area residents.
- **Avg. Area House Age**: Average age of houses in the area.
- **Avg. Area Number of Rooms**: Average number of rooms per house in the area.
- **Avg. Area Number of Bedrooms**: Average number of bedrooms per house in the area.
- **Area Population**: Population of the area.
- **Price**: Target variable, representing the price of the house.
- **Address**: Address of each house (not used in the model).

### Data Source
The dataset used here was created for the purpose of this project. *(Add link or credit to data source if applicable)*

### Data Exploration and Visualization
Exploratory data analysis includes:
- **Correlation Analysis**: Studying relationships between features using pair plots and correlation heatmaps.
- **Distribution Plots**: Visualizing the distribution of target and feature variables for insights on skewness and range.

## Project Structure
USA_household_Project/  
├── data/                     # Folder containing the dataset  
├── notebooks/                # Jupyter notebook for analysis and modeling  
├── src/                      # Scripts for data processing and model training  
│   ├── data_preprocessing.py # Data preprocessing script  
│   ├── model.py              # Script for model training and evaluation  
├── results/                  # Folder for saving results and evaluation metrics  
├── README.md                 # Project documentation  
└── requirements.txt          # Python dependencies  


## Installation
1. **Clone the repository**:
   
   ```bash
   git clone https://github.com/CodeVenger1/USA_household_Project.git

2. **Navigate to the project directory**:

    ```bash
    cd USA_household_Project

3. **Install the required packages**:

    ```bash
    pip install -r requirements.txt

## Usage
1. **Open the Jupyter Notebook**:
   - Run the notebook `Usa_housing-Linear Regression Project.ipynb` for data exploration, visualization, and model training.

2. **To preprocess data and train the model**:
   - **Data Preprocessing**: Run the `data_preprocessing.py` script to clean and prepare the dataset.
   - **Model Training**: Run `model.py` to train the linear regression model on preprocessed data.

3. **Evaluate Model**:
   - The notebook and scripts include model evaluation using metrics like **Mean Absolute Error (MAE)**, **Mean Squared Error (MSE)**, and **Root Mean Squared Error (RMSE)**.

## Results
The linear regression model's performance is evaluated with:
- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- **Root Mean Squared Error (RMSE)**

These metrics provide insights into the model’s accuracy in predicting housing prices.

## Future Improvements
- **Feature Engineering**: Add features like proximity to amenities or school quality.
- **Alternative Models**: Try other algorithms like Random Forest or XGBoost.
- **Hyperparameter Tuning**: Optimize parameters for better accuracy.

## Contributing
Contributions are welcome! Please:
 1. Fork the repository.
 2. Create a new branch for your feature or bug fix.
 3. Submit a pull request with details on the changes.




