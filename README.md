# Fitbit Calorie Prediction with Machine Learning

This project leverages the Kaggle Fitbit dataset to analyze activity metrics and predict daily calorie expenditure using machine learning models. The project includes a user interface for model selection and input customization.

## Features

- **Dataset Analysis**: Exploratory data analysis of the Fitbit activity dataset.
- **Model Training**: Implements machine learning models including:
  - XGBoost
  - Long Short-Term Memory (LSTM)
- **User Interface**: Interactive UI to select models and input activity data.
- **Visualization**: Graphical representations of predictions and model performance.

## Dataset

The dataset is sourced from the [Kaggle Fitbit Dataset](https://github.com/mrudulapatteparapu/kaggle-fitbit-dataset), specifically the `dailyActivity_merged.csv` file. It contains the following key features:
- `TotalSteps`, `TotalDistance`
- `VeryActiveMinutes`, `FairlyActiveMinutes`, `LightlyActiveMinutes`
- `Calories`

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Jahobie/Calorie-Prediction-Comparison-of-Machine-Learning-Models
   ```

2. Navigate to the project directory:
   ```bash
   cd Calorie-Prediction-Comparison-of-Machine-Learning-Models
   ```

3. Install all dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Dependencies

The following libraries and tools are required for this project:

- **Programming Language**: Python 3.8+
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - XGBoost
  - TensorFlow/Keras
  - Scikit-learn

## Usage

1. Open the Jupyter notebook file `ML_Project_UI_Working.ipynb` in Jupyter Notebook or Jupyter Lab:
   ```bash
   jupyter notebook ML_Project_UI_Working.ipynb
   ```
2. Run the cells step-by-step:
   - Load the dataset.
   - Perform exploratory data analysis (EDA).
   - Train machine learning models (XGBoost or LSTM).
   - Test predictions on input activity data or a batch of data.

3. Use the provided interface to:
   - Select a model (XGBoost or LSTM).
   - Input activity data or select batch data from the dataset.
   - View predictions and performance metrics through visualizations.


