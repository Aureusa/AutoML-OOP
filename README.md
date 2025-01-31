# AutoML-OOP with Streamlit

![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)  
**AutoML-OOP** is an interactive web application built with Streamlit that automates machine learning workflows using an Object-Oriented Programming (OOP) approach. This tool allows users to upload datasets, configure preprocessing steps, train models, and evaluate results—all through a user-friendly interface.

---

## Features

- **Interactive Web Interface**: Built with Streamlit for seamless user interaction.
- **Automated Machine Learning**:
  - Data preprocessing.
  - Model selection (classification and regression models).
- **Real-Time Visualization**:
  - Display model performance metrics (accuracy, RMSE, ROC curves).
- **Customizable Workflow**: Extend or override components (preprocessors, models, etc.) via Python classes.

---

## Quick Start

### Installation

1. **Clone the repository**:
    ```
    git clone https://github.com/Aureusa/AutoML-OOP.git
    cd AutoML-OOP
    ```

2. **Install dependencies**:
    ```
    pip install -r requirements.txt
    ```

3. **Run the Streamlit app**:
    ```
    streamlit run app.py
    ```

---

## Usage Guide

### Step 1: Launch the App
After running `streamlit run app.py`, the app will open in your default browser at `http://localhost:8501`.

### Step 2: Upload Your Dataset
- Upload a CSV or Excel file via the sidebar.
- Select the target variable for prediction.

### Step 3: Configure Preprocessing
- Choose the desired features

### Step 4: Select and Train Models
- Pick a task type (**Classification** or **Regression**).
- Select models
- Adjust hyperparameters using sliders or dropdowns.

### Step 5: Evaluate Results
- View real-time performance metrics.

---

## Bonus

There is an added pricepredictor that the user can use to predict the next N (max 5) closing prices on the stockmarket data of Apple and Microsoft.

---

## License

This project is licensed under the All Rights Reserved License. See [LICENSE](LICENSE) for details.
