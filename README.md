

**Name:** Nishita Sharma  
**Company:** CODTECH IT SOLUTIONS  
**ID:** CT4DA5432  
**Domain:** Data Analytics  
**Duration:** July 2024 To August 2024  
**Mentor:** Muzammil Ahmed  

---

## Overview of the Project

### Project: Stock Price Prediction using LSTM

**Description:**  
This project utilizes Long Short-Term Memory (LSTM) networks, a type of recurrent neural network (RNN), to predict stock prices. By analyzing historical stock price data, the model aims to predict future prices, aiding investors in making informed decisions.

**Objective:**  
The primary objective of this project is to build a predictive model using LSTM to forecast stock prices. By doing so, we aim to help investors and financial analysts understand stock price trends and make better investment decisions.

---

## Key Activities

1. **Data Loading and Exploration:** 
    - Loaded the stock price dataset.
    - Explored the data to understand its structure and contents.

2. **Data Preprocessing:**
    - Reset the index and extracted the 'close' price.
    - Scaled the data using MinMaxScaler to normalize the values.

3. **Data Splitting:**
    - Split the data into training and testing sets with a 65-35 ratio.

4. **Dataset Creation:**
    - Created a function to generate the dataset for the LSTM model with a specified time step.

5. **Model Building:**
    - Built an LSTM model with three LSTM layers and one Dense layer.
    - Compiled the model using 'mean_squared_error' loss and 'adam' optimizer.

6. **Model Training:**
    - Trained the model on the training data and validated it on the test data over 100 epochs.

7. **Prediction:**
    - Made predictions on both training and test datasets.
    - Inversed the scaled predictions to obtain actual values.

8. **Performance Evaluation:**
    - Evaluated the model's performance using Root Mean Squared Error (RMSE).

9. **Future Prediction:**
    - Predicted future stock prices for the next 30 days.

10. **Visualization:**
    - Visualized the actual vs. predicted stock prices.
    - Plotted future stock price predictions.

---

## Technologies Used

- **Python:** For data manipulation and analysis.
- **Pandas:** For data manipulation and preprocessing.
- **Numpy:** For numerical computations.
- **Matplotlib:** For data visualization.
- **Scikit-learn:** For data preprocessing.
- **TensorFlow & Keras:** For building and training the LSTM model.

---

## Key Insights

- **Model Performance:** The LSTM model effectively learned from historical stock price data and made accurate predictions.
- **Future Predictions:** The model provided reasonable future stock price predictions, demonstrating its potential use in real-world scenarios.
- **Data Scaling:** Normalizing the data significantly improved the model's performance and training efficiency.
- **Visualization:** The visualizations helped in understanding the model's predictions and comparing them with actual stock prices.

---

## Conclusion

The project successfully utilized LSTM to predict stock prices. The insights gained from this analysis can help investors and financial analysts understand stock price trends and make better investment decisions. By predicting future stock prices, this model can serve as a valuable tool in the financial domain.

