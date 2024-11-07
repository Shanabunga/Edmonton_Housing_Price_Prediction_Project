# 🏠📈 Edmonton Housing Price Prediction Project 🌆🏠

This project aims to predict housing prices in Edmonton, Alberta, using various features such as property age, location, and zoning. It supports homeowners and investors in making informed property decisions through data analysis and machine learning models.

![Final ML Model](https://github.com/Shanabunga/Edmonton_Housing_Price_Prediction_Project/assets/67124092/2ae4ed41-de76-4555-bf95-fef97665078e)

## **Project Overview**
This analysis uses historical property data to identify trends and predict property values, helping homeowners find high-value neighborhoods and assisting investors with pricing insights for property investments.

## **Business Challenge**
- **For Homeowners**: Identify high-value neighborhoods suitable for long-term investment.
- **For Investors**: Forecast property prices based on critical features like location, zoning, and age.

## **Data Preparation**
Key steps included:
- Filtering to recent years (2019-2021) and focusing on residential zones.
- Conducting EDA to analyze complete records, targeting assessed value, garages, and build year.
- Engineering “Age of Property” and excluding entries with missing data for location and property age.

## **Key Insights**
- **Dashboard**: A Tableau dashboard visualizes property values, garage availability, build year, and zoning. [View Dashboard](#)
- **Feature Importance**: Property value showed correlations with features like garage presence, newer build years, and specific zoning types.

## **Modeling Approach**
We tested three models to identify the best approach for accurate price predictions:
1. **Ridge Regression**: Initial trials had low precision (R² = 0.21).
2. **Random Forest Regressor**: Achieved best results with R² = 0.86 and a reduced Mean Squared Error.
3. **Gradient Boosting Regressor**: Delivered stable performance with R² = 0.72.

## **Results**
- The **Random Forest Regressor** model, with R² = 0.86, provided the most accurate predictions, effectively identifying high-value properties.

## **Future Work**
To further enhance accuracy and insights:
- Integrate neighborhood crime and census data.
- Address missing values, especially for location and build year.
- Refine zoning categories to better target specific property types.
