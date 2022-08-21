# EDA-FeatureEngineering-Booking-Reviews
Analysis of the reviews from Booking.com to predict the rating of a hotel.

- The nltk library and the SentimentIntensityAnalyzer() class are used to generate new features. This approach is the right way to create features that will affect the target variable when building the model.
- Feature encoding is used using OneHotlEncoder().
- For feature selection, multicollinearity (.corr) and feature significance (f_classif) analysis was performed. The results are presented in the form of graphs using the matplotlib and seaborn libraries.
- The resulting model is quite good at improving the value of the final MAPE metric for the baseline.
