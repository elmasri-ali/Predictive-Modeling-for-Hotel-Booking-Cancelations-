
# Predictive Modeling for Hotel Booking Cancellations

This repository contains the code and resources used for developing predictive models to forecast hotel booking cancellations. The project explores different machine learning techniques to predict whether a booking will be canceled based on a variety of features related to the booking and customer behavior.

## Project Structure

- **Data/**: This folder is intended to store the dataset used in the project. Please download the data from the source and place it in this folder.
- **Notebooks/**: Contains Jupyter notebooks used for data analysis, model development, and visualization. Each notebook is explained in detail below.
- **requirements.txt**: Lists all the dependencies and their versions used in this project. Install them using the following command:
  ```
  conda install --yes --file requirements.txt

  ```

## Dataset

The dataset used in this project is the "Hotel Booking Demand" dataset, which can be downloaded from [Kaggle](https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand). 

After downloading, place the dataset file (e.g., `hotel_bookings.csv`) into the `Data/` folder.

## Notebooks

- **1-Eda-and-Basemodels.ipynb**: This notebook performs the initial exploration and preprocessing of the dataset, followed by the development of baseline models.
- **2-GridSearch.ipynb**: Focuses on hyperparameter tuning using GridSearchCV and RandomizedSearchCV to optimize model performance.
- **3-Weighted.ipynb**: Explores handling class imbalance using weighted classes and compares it with SMOTE.
- **4-Final.ipynb**: Compares various models and selects the best-performing one based on several metrics.
- **5-Visuals.ipynb**: Contains visualizations of the model performance and key aspects of the dataset.

## Installation

To replicate this environment, follow these steps:

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo-name.git](https://github.com/elmasri-ali/Predictive-Modeling-for-Hotel-Booking-Cancelations-.git
   ```

2. Navigate to the project directory:
   ```
   Predictive-Modeling-for-Hotel-Booking-Cancelations-
   ```

3. Install the required packages using the `requirements.txt` file:
   ```
   pip install -r requirements.txt 
   ```

4. If you're using conda, you can create an environment from the exported environment file (assuming you have exported it):
   ```
   conda env create -f environment.yml
   ```

## Usage

Run the notebooks in the `Notebooks/` folder in the order they are listed to replicate the analysis and modeling steps.

## License

This project is licensed under the MIT License.
