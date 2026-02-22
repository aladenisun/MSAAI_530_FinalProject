# Smart Home Air Quality Monitoring with IoT and Machine Learning
## Project Overview
This project explores how Internet of Things (IoT) sensing and machine learning can be combined to understand and anticipate indoor environmental conditions. Using multivariate gas sensor data along with temperature and humidity measurements, the system monitors air behavior over time and predicts near-future changes before they fully occur.

The goal is to move beyond passive monitoring and provide early awareness of environmental changes inside a home environment.

The project includes:
- Data preprocessing and exploratory analysis
- Traditional time-series regression forecasting
- Deep learning forecasting using LSTM
- Visualization through an interactive Tableau dashboard

## Dataset
Gas Sensors for Home Activity Monitoring
Source: UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/362/gas+sensors+for+home+activity+monitoring

The dataset contains time-series recordings from asensor array consisting of:
- 8 metal oxide gas sensors (R1–R8)
- Temperature
- Relative humidity

Data was recorded in a real home environment and includes background air as well as odor events (banana and wine).

## Models Implemented
1. Traditional Time-Series Regression (Linear and Ridge Regression)
2. LSTM Neural Network

## System Workflow
1. Raw sensor data is cleaned and structured as time-series data
2. Sliding window sequences are created for prediction tasks
3. Two predictive models are trained
4. Regression model forecasts short-term values (R3, R4)
5. LSTM model learns longer temporal dependencies
6. Predictions and sensor trends are visualized in Tableau


## Tableau Public Dashboard
The Tableau dashboard link: https://public.tableau.com/views/AAI530_17716614216890/SmartHomeGasSensorMonitoringDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Team Members
- Rogelio Aguilar
- Nisun Alade
- Zinah Othman
