# Crack The Code of Hair Loss
## 📖 Background:
As we age, hair loss becomes one of the health concerns of many people. The fullness of hair not only affects appearance, but is also closely related to an individual's health.
A survey brings together a variety of factors that may contribute to hair loss, including genetic factors, hormonal changes, medical conditions, medications, nutritional deficiencies, psychological stress, and more. 
Through data exploration and analysis, the potential 
correlation between these factors and hair loss can be deeply explored, thereby providing useful reference for the development of individual health management, medical intervention and related industries.

## Key Insights:
- The dataset contains 999 rows and 13 columns. There are no null values. I renamed some columns with leading spaces.
- No data values in 'Medical Conditions', 'Medications & Treatments', 'Nutritional Deficiencies' columns might be the absence of a certain health issue; I replace them with the numpy null values
- The average age is 34 years and the distribution shows a somewhat bimodal distribution with significant peaks, especially at 35.
- Alopecia Areata is the most common health condition with about 12% of the overall data.
- There are 10 types of Nutritional Deficiencies with Zinc Deficiency being the most common
- The probability of losing Hair between 31-40 is a bit higher compared to other groups
- A little more people under a moderate stress level lose their hair compared to the low and high stress level
- There is no statistically significant difference between Hair loss and the other variables except the Age variable
- 49.7% is the percentage of hair loss in this dataset
- - Used a Decision Tree as the baseline model and a Random Forest Classifier as a Comparison model, The comparison model performed slightly better so I applied the RandomizedCV to improve its performance.
- With an Accuracy of 54% the model might be only slightly better than random guessing
- Age and stess are the two most important features for the model's prediction

## Recommendation:
- Age is a very important factor when it comes to hair loss, investigating what causes hair loss between 30 and 40 years might be a good idea.
- Increasing the dataset's size will bring diversity and might help get better Accuracy.

