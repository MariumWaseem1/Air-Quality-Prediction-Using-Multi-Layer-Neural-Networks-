# Air Quality Classifier – INM702 Task 1

This project classifies air quality into four categories using a custom neural network built entirely with NumPy. Developed for the INM702 coursework.

## Dataset

\- Source: Air Quality & Pollution Assessment (Kaggle)  
\- Features: Temperature, Humidity, PM2.5, PM10, NO2, SO2, CO, Proximity to Industrial Areas, Population Density  
\- Target: Air quality class (Good, Moderate, Poor, Hazardous)

## Techniques Used

\- Data preprocessing with StandardScaler and one-hot encoding  
\- Class imbalance handled using SMOTE  
\- Custom neural network built from scratch using NumPy  
\- 3-layer dense network with ReLU and Softmax  
\- Optimization: Batch and mini-batch gradient descent  
\- Regularization: Dropout (0.05) using inverted dropout scaling

## Results

\- Batch Gradient Descent Accuracy: 93.44%  
\- Mini-batch Gradient Descent Accuracy: 91.63%

## Future Work

\- Integrate real-time sensor data  
\- Improve feature engineering  
\- Compare with deep learning models using PyTorch or TensorFlow

## Project Structure

task1_air_quality/  
\- data/                  - Processed dataset files  
\- nn_numpy/              - Custom NN implementation  
\- preprocessing/         - Feature engineering and SMOTE  
\- training/              - Batch and mini-batch training scripts  
\- README.md              - This documentation

## Authors

\- Marium Waseem  
\- Kovarthanan Kesavan


