# Taxi Fare Prediction

Project URL: https://github.com/GNair06/taxi_fare

This project aims to develop predictive models to estimate the total amount paid by travelers for taxi rides. By utilizing a dataset containing various features of taxi rides, including pickup/dropoff times, locations, passenger count, and trip distance, we will build models to predict the `total_amount` for taxi fares.

## Dataset Overview

The dataset provides the necessary information to construct predictive models that estimate the total fare (`total_amount`) paid by travelers. It consists of the following files:

- **train.csv**: The training set containing both feature attributes and the target variable `total_amount`.
- **test.csv**: The test set with feature attributes similar to the training set, but without the target variable `total_amount` (this is the variable to predict).
- **sample_submission.csv**: A sample submission file formatted for competition submissions.

## Data Files

- `train.csv`: Contains features and the target variable `total_amount`.
- `test.csv`: Contains features only, to be used for predictions.
- `sample_submission.csv`: An example submission file in the required format.

## Columns Description

The dataset includes various features that describe taxi rides. Key columns are as follows:

- **total_amount**: The total fare paid by the traveler for the ride (target variable).
- **VendorID**: Identifier for taxi vendors.
- **tpep_pickup_datetime**: Timestamp when the ride started (pickup time).
- **tpep_dropoff_datetime**: Timestamp when the ride ended (dropoff time).
- **passenger_count**: The number of passengers during the ride.
- **trip_distance**: The distance traveled during the ride.
- **RatecodeID**: Rate code used for the ride.
- **store_and_fwd_flag**: Indicates if the trip record was stored and forwarded due to the vehicle being offline.
- **PULocationID**: Pickup location identifier.
- **DOLocationID**: Dropoff location identifier.
- **payment_type**: The type of payment used for the ride.

Additional columns provide further context to the taxi rides and can be used in the modeling process.

## Project Goals

The goal of this project is to leverage the dataset features to build robust predictive models that accurately estimate the `total_amount` of taxi fares. Participants are encouraged to explore different modeling techniques and evaluate their performance using metrics such as RMSE (Root Mean Square Error) or MAE (Mean Absolute Error).

## How to Use the Dataset

1. **Training**: Use `train.csv` to train your predictive models. This file contains both the features and the target variable (`total_amount`).
2. **Testing**: Use `test.csv` to generate predictions. This file does not include the target variable, as your model will predict the `total_amount`.
3. **Submission**: After generating predictions for the test set, submit your results using the `sample_submission.csv` format.

## How to Run the Project

1. Clone this repository:

   ```bash
   git clone https://github.com/GNair06/taxi_fare.git
   cd taxi_fare
