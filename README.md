Overview
This project predicts house prices based on various features like the number of bedrooms, bathrooms, square footage, year built, and more. It also recommends similar houses from a dataset based on the predicted price. The project is built using Flask for the web application, Pandas for data processing, and Scikit-Learn for model predictions.

Features
Predict house prices based on features such as:
Number of bedrooms
Number of bathrooms
Square footage of living area and lot
Number of floors
Year built and year renovated
City
Recommend similar houses based on the predicted price.
Display images for the recommended houses.
Responsive and interactive frontend.
Tech Stack
Backend: Flask (Python)
Machine Learning: Scikit-Learn
Data Processing: Pandas
Dataset: House data loaded from a CSV file
Making Predictions
Fill in the form with house details like bedrooms, bathrooms, etc. Click on the "Predict House Price" button to see the predicted price. If similar houses are found, they will be listed along with their images. Dataset The dataset (combined_data.csv) contains information about houses, including:

Price
Number of bedrooms and bathrooms
Square footage of living area, lot, and basement
Year built and renovated
City
You can update this dataset with new data or preprocess it to remove any missing or irrelevant values. To do that, make sure you edit the values in the data_ingestion.py , data_transformation.py, model_trainer.py and modify pridict.html according to your dataset features.

Models
The house price prediction model is built using Scikit-Learn's regression models. A recommendation system is also in place, which compares the predicted price with other houses in the dataset and suggests similar ones.

Issues and Contributions
If you encounter any issues, feel free to submit them in the Issues section. Contributions are welcome!
