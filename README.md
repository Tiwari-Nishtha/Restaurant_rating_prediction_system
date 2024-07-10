Restaurant Ratings Prediction

This project aims to predict restaurant ratings using regression algorithms. The dataset used includes various features such as location, cuisines, and other restaurant attributes.

TABLE OF CONTENTS

* Dataset
* Preprocessing
* Models
* Evaluation
* Feature Importance
* Installation
* Usage
* Contributing
* License
* Dataset

THE DATASET USED IN THIS PROJECT CONTAINS INFORMATION ABOUT RESTAURANTS, INCLUDING

* Country Code
* City
* Cuisines
* Currency
* Has Table booking
* Has Online delivery
* Is delivering now
* Switch to order menu
* Rating color
* Rating text
* Aggregate rating (target variable)

  
PREPROCESSING

1. Handling Missing Values:
* Numerical missing values are filled with the mean.
* Categorical missing values are filled with the mode.

2. Encoding Categorical Variables:
* Categorical variables are converted into dummy/indicator variables.

3. Splitting the Data:
* The dataset is split into training and testing sets with an 80-20 ratio.
Models

TWO REGRESSION ALGORITHMS ARE USED IN THIS PROJECT
* Linear Regression
* Decision Tree Regression
  
EVALUATION

The models are evaluated using the following metrics:

* Mean Squared Error (MSE)
* R-squared (R²)

FEATURE IMPORTANCE

* The feature importance is calculated for the Decision Tree model and visualized using a bar plot.

INSTALLATION

Clone the repository:


Copy code:

    git clone https://github.com/your-username/restaurant-ratings-prediction.git

    cd restaurant-ratings-prediction


Install the required packages:


    pip install -r requirements.txt

USAGE

Ensure you have the dataset file (Dataset.csv) in the project directory.


Run the script:

    python main.py

The results, including model performance and feature importance plot, will be displayed.

CONTRIBUTING

Contributions are welcome! Please feel free to submit a Pull Request.


LICENSE

This project is licensed under the MIT License.

