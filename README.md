# Predictive Maintenance for Conveyor Belts

This project focuses on predictive maintenance for conveyor belts using machine learning, specifically LSTM (Long Short-Term Memory) neural networks. The goal is to detect potential failures in conveyor belt systems by analyzing sensor data. The project consists of several tasks, including data simulation, data preprocessing, model creation, training, and real-time simulation.

## Table of Contents
- [Task 1: Data Simulation](#task-1-data-simulation)
- [Task 2: Data Preprocessing](#task-2-data-preprocessing)
- [Task 3: LSTM Model](#task-3-lstm-model)
- [Task 4: Model Training](#task-4-model-training)
- [Task 5: Real-time Simulation](#task-5-real-time-simulation)
- [Running the Code](#running-the-code)

## Task 1: Data Simulation
In this task, we generate synthetic data representing sensor readings over time for conveyor belt systems. The data includes temperature, vibration, and belt speed. We also introduce failure scenarios with adjustable probabilities. The functions provided simulate both failure detection and non-detection scenarios.

## Task 2: Data Preprocessing
The generated data is preprocessed, which includes converting data to the appropriate format, handling missing values, and normalizing the data using the StandardScaler. The data is also split into training and testing sets.

## Task 3: LSTM Model
An LSTM model is created using TensorFlow and Keras. The model architecture consists of LSTM layers and an output layer. The model is compiled with appropriate loss functions and optimizers.

## Task 4: Model Training
The LSTM model is trained using the preprocessed training data. The number of epochs and batch size can be adjusted for training. Training progress is monitored, and the model's performance is evaluated on the testing data.

## Task 5: Real-time Simulation
A function is provided to simulate real-time data from conveyor belts. The trained LSTM model is then used to make predictions on the real-time data. Alerting logic is implemented to notify maintenance teams when a failure is predicted.

## Running the Code
To run the code, follow these steps:

1. Ensure you have Python, TensorFlow, scikit-learn, and other required libraries installed.

2. Run the code sequentially, starting with Task 1 and proceeding to Task 5.

3. The code will simulate data, preprocess it, create and train the LSTM model, and finally simulate real-time data and make predictions.

4. Adjust parameters, such as the number of sequences, sequence length, and failure probabilities, to match your specific use case.

5. Monitor the model's predictions and adapt the alerting logic as needed for your maintenance scenario.

This README provides a high-level overview of the predictive maintenance assignment. Each task in the code includes detailed comments to help you understand and modify the code as necessary for your project.

For any questions or assistance, feel free to reach out.

Best regards,
Khaydarov Shokhzod.
