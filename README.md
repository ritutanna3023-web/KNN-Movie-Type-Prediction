# KNN Movie Type Prediction

## Project Overview

This project uses the **K-Nearest Neighbors (KNN)** classification algorithm to predict a movie's type based on its rating and duration.

The project uses a small sample dataset containing movie ratings, durations, and types such as Action and Comedy.

## Technologies Used

* Python
* Pandas
* Scikit-learn
* Jupyter Notebook

## Dataset

The dataset contains three columns:

* **Rating:** Movie rating
* **Duration:** Movie duration in minutes
* **Type:** Movie category (Action or Comedy)

## Algorithm

K-Nearest Neighbors (KNN) is a supervised machine learning algorithm used for classification.

In this project:

* The number of neighbors (`k`) is set to 3.
* The model learns from the training data.
* It predicts the type of a new movie based on the nearest examples.

## Example Prediction

The project uses the following example:

* Movie: Housefull
* Rating: 7.4
* Duration: 114 minutes

The trained model predicts a movie type based on the sample data.

## How to Run

1. Clone or download this repository.

2. Install the required libraries:

   ```bash
   pip install pandas scikit-learn jupyter
   ```

3. Open Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

4. Open `KNN_Movie_Prediction.ipynb`.

5. Run all cells.

## Limitations

This is a beginner-level educational project using only four sample records. Its predictions are not reliable for real-world movie classification.

## Learning Outcomes

* Understanding features and target variables
* Creating a Pandas DataFrame
* Training a KNN classification model
* Predicting categories for new data
* Understanding the importance of feature scaling
