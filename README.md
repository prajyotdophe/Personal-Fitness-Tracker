# Personal Fitness Tracker

## Overview

The **Personal Fitness Tracker** is a web application built with Streamlit that allows users to predict the number of kilocalories burned based on personal input parameters such as age, BMI, duration of exercise, heart rate, body temperature, and gender. The app utilizes machine learning models, specifically Random Forest Regressor, to provide accurate calorie burn predictions based on user data.

## Features

- **User Input Panel:** Users can enter their age, BMI, exercise duration, heart rate, body temperature, and gender.
- **Calorie Prediction:** A trained Random Forest Regressor predicts the calories burned based on user input.
- **Comparison with Others:** The app provides statistical comparisons with other users based on the dataset.
- **Similar Results:** It fetches records from the dataset that have similar calorie burn estimates.
- **Interactive Visuals:** Uses progress bars and tables for better user experience.

## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/fitness-tracker.git
   ```
2. Navigate to the project directory:
   ```sh
   cd fitness-tracker
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

1. Run the Streamlit app:
   ```sh
   streamlit run app.py
   ```
2. Open your web browser and navigate to the URL displayed in the terminal.
3. Enter your fitness parameters and view the predicted calorie burn.

## Dependencies

- `streamlit`
- `numpy`
- `matplotlib`
- `seaborn`
- `pandas`
- `scikit-learn`

## Data Sources

The application utilizes `calories.csv` and `exercise.csv` datasets, which contain records of users’ exercise data along with calories burned.

## Future Improvements

- Add support for additional machine learning models.
- Implement user authentication for tracking personal fitness history.
- Enhance UI with interactive graphs and charts.

## Contributing

Contributions are welcome! Feel free to fork the repo and submit a pull request with improvements.

