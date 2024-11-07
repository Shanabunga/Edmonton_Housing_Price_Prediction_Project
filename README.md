# Edmonton Housing Price Prediction Project

**Project Overview**<br>
This project predicts housing prices in Edmonton, Alberta, helping homeowners and investors make informed property decisions by analyzing factors like property age, location, and zoning.

![Final ML Model](https://github.com/Shanabunga/Edmonton_Housing_Price_Prediction_Project/assets/67124092/2ae4ed41-de76-4555-bf95-fef97665078e)

**Business Challenge**<br>
Our goals included:
- Assisting homeowners in finding high-value neighborhoods.
- Enabling investors to predict home prices based on property features and location.

**Data Preparation**<br>
Key steps included:
- Filtering data to recent years (2019-2021) and residential zones.
- Conducting EDA to focus on complete data, targeting assessed value, garages, and build year.
- Engineering “Age of Property” and removing entries with missing location and age values.

**Key Insights**<br>
- Dashboard: A Tableau dashboard visualizes property values, garage availability, build year, and zoning. View Dashboard
- Feature Importance: Notable correlations include property value with garage presence, newer build years, and certain zoning types.

**Modeling Approach**<br>
We tested three models:
- Ridge Regression: Initial trials with low precision (R² = 0.21).
- Random Forest Regressor: Achieved best results (R² = 0.86, MSE reduced).
- Gradient Boosting Regressor: Stable performance (R² = 0.72).

**Results**<br>
 - The Random Forest Regressor model, with R² = 0.86, accurately predicted property values and targeted high-value properties.

**Future Work**<br>
Enhancements include:
- Integrating neighborhood crime and census data.
- Addressing missing values for location and build year.
- Refining zoning categories to better target property types.
