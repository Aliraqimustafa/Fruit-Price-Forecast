# Fruit Price Forecast

![images](https://raw.githubusercontent.com/Aliraqimustafa/Fruit-Price-Forecast/main/OIG.jfif)

Welcome to the Fruit-Price-Forecast repository! In this project, I have developed a model to forecast the prices of fruits and vegetables in India. The data used for this project is sourced from Kaggle's [Vegetable and Fruits Price in India dataset](https://www.kaggle.com/datasets/raghu07/vegetable-and-fruits-price-in-india). I have reprocessed the data to prepare it for building artificial intelligence models.

## Model Details

I have utilized a Random Forest model, which has demonstrated remarkable performance. Here are the details of the model's accuracy:

- **Training Accuracy:** 99.9%
- **Test Accuracy:** 99.1%

## How to Use the Model

To use this model and predict the price of a fruit or vegetable, follow these steps:

### 1. Download the Encoder:

- Download the `encoder.pkl` file attached to this repository. This file contains the list of all fruits and vegetables the model was trained on.
- Use the following code snippet to load the encoder in your Python environment:

  ```python
  import joblib

  file_path = 'encoder.pkl'
  loaded_encoder = joblib.load(file_path)
  ```
### 2. Provide Input

- **Fruit or Vegetable Name:** Ensure the name of the fruit or vegetable you want to predict the price for is in the list of classes from the encoder.
- **Date:** Specify the date for which you want to forecast the price.

### 3. Make a Prediction

Utilize the loaded encoder and the specified date to predict the price using the trained model.

## Additional Resources

- The pre-trained Random Forest model can be downloaded from [RF Model](https://drive.google.com/file/d/1jmFS4DESM83onP992VxInyNabr8zAcT6/view?usp=sharing).
- Download the data after reprocessing it to be ready to train models [Pre-Processed Data](https://drive.google.com/file/d/1NXk6vnS9MkmhOOD30VEO28BJ8yt4uOXQ/view?usp=sharing).

## Contact Information

If you have any questions or need further assistance, feel free to reach out to me:

- **Telegram:** [Tele_URL](https://t.me/ha12qw)
- **Facebook:** [Mustafa Mohammad]([https://www.facebook.com/your_facebook_profile](https://www.facebook.com/profile.php?id=100049592914479)https://www.facebook.com/profile.php?id=100049592914479)

Happy predicting!
