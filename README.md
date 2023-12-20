# Machine Learning Model for Weather Forecasting

## Project Purpose

The primary objective of this project is to predict temperature using machine learning algorithms, specifically Linear Regression, Decision Tree Regression, and Random Forest Regression. The prediction is based on various input factors such as maximum temperature, minimum temperature, cloud cover, humidity, sun hours in a day, precipitation, pressure, and wind speed.

## Usage of Algorithms

The project employs different machine learning algorithms for temperature prediction. Training is performed using 80% of the dataset, and the remaining 20% is used as a test set. For instance, to forecast the temperature of Kanpur, India, eight years of data is used for training, and two years serve as the test dataset. The algorithms utilized include Linear Regression, Decision Tree Regression, and Random Forest Regression. Unlike traditional weather forecasting, which relies heavily on simulation based on physics and differential equations, this project leverages artificial intelligence for temperature prediction, providing accurate and predictive results.

In conclusion, machine learning has significantly transformed the landscape of weather forecasting, enhancing accuracy and predictability. Future advancements are expected to further improve the precision of weather predictions, aiding in the prevention of disasters such as hurricanes, tornadoes, and thunderstorms.

## Methodology

### Dataset
The dataset for this project is sourced from Kaggle, titled "Historical Weather Data for Indian Cities." The specific data selected pertains to Kanpur City. The dataset spans from 01-01-2009 to 01-01-2020, and the hourly weather data was obtained using the worldweatheronline.com API and the wwo_hist package. While the data extraction method involves the API, it's important to note that the accuracy of the data cannot be guaranteed.

The dataset is intended for various purposes, including visualizing changes due to global warming and predicting weather for upcoming days, weeks, months, and seasons. The extensive data can also be used for visualization to understand the impact of global warming on weather aspects such as precipitation, humidity, and temperature.

### Project Focus
The primary focus of the project is on temperature prediction for Kanpur City. Multiple machine learning algorithms and regression techniques are applied to the historical weather dataset. The sequence of regression models includes Multiple Linear Regression, Decision Tree Regression, and Random Forest Regression.

## Repository Structure

- **data:** Contains the historical weather dataset.
- **notebooks:** Jupyter notebooks used for data analysis, model training, and evaluation.
- **src:** Source code for the machine learning models.
- **docs:** Documentation related to the project, including this README file.

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/Machine-Learning-Weather-Forecasting.git
   cd Machine-Learning-Weather-Forecasting
   ```

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Explore the notebooks in the `notebooks` directory for detailed analysis and model training.

4. Run the machine learning models using the scripts in the `src` directory.

Feel free to customize and extend the project according to your needs. If you have any questions or suggestions, please open an issue in the repository.
