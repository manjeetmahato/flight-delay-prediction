# Predicting Flight Delay Using Advanced Machine Learning Algorithms

This project aims to predict flight delays using advanced machine learning algorithms. The goal is to predict whether a flight will be delayed based on various factors such as flight details, origin and destination airports, and historical performance.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Google Colab Notebook](#google-colab-notebook)

## Project Overview
The project uses a dataset of flight records to predict delays. The dataset includes information like departure times, flight distance, airline, origin, and destination airports. Machine learning models such as Random Forest Classifier and Gradient Boosting Classifier are used to build the predictive model.

## Dataset
The dataset contains the following features:

- **Day of Month**: The day of the month the flight was scheduled.
- **Day of Week**: The day of the week starting from Monday.
- **Unique Carrier Code**: Identification number for the airline.
- **Carrier Code (IATA)**: Code assigned by IATA to identify a carrier.
- **Tail Number**: Aircraft identification number.
- **Flight Number**: Flight identification number.
- **Origin Airport ID**: Unique identifier for the origin airport.
- **Origin Airport Sequence ID**: Sequence number for the origin airport.
- **Origin Airport**: Name of the origin airport.
- **Destination Airport ID**: Unique identifier for the destination airport.
- **Destination Airport Sequence ID**: Sequence number for the destination airport.
- **Destination Airport**: Name of the destination airport.
- **Actual Departure Time**: Scheduled departure time (hhmm format).
- **Departure Delay Indicator**: Whether the departure delay was 15 minutes or more (1 = Yes, 0 = No).
- **Departure Time Block**: Hourly intervals indicating the departure time.
- **Actual Arrival Time**: Actual arrival time (hhmm format).
- **Arrival Delay Indicator**: Whether the arrival delay was 15 minutes or more (1 = Yes, 0 = No).
- **Cancelled Flight Indicator**: Indicates if the flight was cancelled (1 = Yes, 0 = No).
- **Diverted Flight Indicator**: Indicates if the flight was diverted (1 = Yes, 0 = No).
- **Distance**: Distance between the origin and destination airports (in miles).
- **Unnamed: 21**: No description available.

## Google Colab Notebook
The project is implemented in a Google Colab notebook. You can access and run the notebook directly by opening the following link:
- [Flight Delay Prediction - Colab Notebook](https://colab.research.google.com/drive/10DoN4Kf9f1kTJSAW_Mg2ZbMPHd3Bh2QQ#scrollTo=bc0a6df4)
