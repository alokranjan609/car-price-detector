# Car Price Predictor

This project is a car price predictor built using a simple linear regression model. The model is deployed using Streamlit, allowing users to interactively predict car prices based on input features.

## Features

- **Simple Linear Regression Model**: A regression model that predicts car prices based on various features.
- **Streamlit Deployment**: An interactive web application to input car features and get price predictions.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/alokranjan609/car-price-detector
    cd car-price-detector
    ```

2. **Install the required packages:**
    ```sh
    pip install -r requirements.txt
    ```
3.**Run the application**
  ```sh
  python -m streamlit run app.py
 ```



## Project Structure

- `app.py`: The main script that runs the Streamlit application.
- `model_saved.pkl':The model which is trained using the dataset.
- `requirements.txt`: List of dependencies required for the project.
- `static/css`:static files for the application.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgements

- The Streamlit team for providing an easy-to-use platform for deploying machine learning models.
- The authors of the datasets used for training the model.

