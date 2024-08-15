# Weather Prediction Project

This project is a weather prediction application that uses machine learning to forecast weather conditions based on input parameters. It includes data analysis, model training, and a graphical user interface for making predictions.

## Features

- Data analysis and visualization of Seattle weather data
- Machine learning model training using various algorithms
- User-friendly GUI for inputting weather parameters and receiving predictions
- Supports predictions for five weather categories: Drizzle, Fog, Rain, Snow, and Sunny

## Dependencies

- Python 3.x
- pandas
- seaborn
- matplotlib
- scipy
- missingno
- scikit-learn
- xgboost
- tkinter

## Installation

1. Clone this repository
2. Install the required packages

## Usage

1. Run the data analysis and model training script
2. Launch the GUI application
3. Enter the weather parameters (precipitation, max temperature, min temperature, and wind speed) in the GUI
4. Click the "Predict Weather" button to see the forecast

## Project Structure

- `weather_analysis.py`: Script for data analysis, visualization, and model training
- `weather_prediction_gui.py`: GUI application for making weather predictions
- `Nb.pkl`: Trained Naive Bayes model file
- `seattle-weather.csv`: Dataset used for training (not included in this repository)

## Model Information

The project uses various machine learning models, including:
- K-Nearest Neighbors
- Support Vector Machine
- Gradient Boosting Classifier
- XGBoost Classifier
- Logistic Regression
- Naive Bayes (used in the final GUI application)

## Future Improvements

- Implement more advanced machine learning models
- Add more detailed weather information and predictions
- Integrate real-time weather data APIs
- Improve the GUI design and user experience

## Contributors

Suhas S Kubasad

## License

This project is open source and available under the [MIT License](LICENSE).
