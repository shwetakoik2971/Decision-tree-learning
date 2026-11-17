# Experiment - Decision Tree Classification (Traffic Prediction)

## Aim

To implement Decision Tree Classification using Python to predict traffic situations.

## Technologies Used
- Python
- Pandas
- Matplotlib
- Scikit-learn
- Label Encoder
- Google Colab
- Decision Tree Classifier

## Dataset

Traffic Dataset (`TrafficDataset (2).csv`)

The dataset contains 2976 records and 8 columns after preprocessing:
- Day of the Week
- Car Count
- Bike Count
- Bus Count
- Truck Count
- Total
- Traffic Situation
- Hour

## Procedure
1. Import the required Python libraries.
2. Load the Traffic dataset using Pandas.
3. Display the first five records.
4. Extract the Hour from the Time column.
5. Remove the Time and Date columns.
6. Convert traffic categories into Normal and Heavy.
7. Convert categorical values into numerical values using Label Encoder.
8. Separate independent variables (X) and dependent variable (y).
9. Select the best four features using SelectKBest.
10. Split the dataset into training and testing sets (80:20).
11. Create a Decision Tree Classifier using Gini criterion.
12. Train the model using training data.
13. Predict traffic situations using testing data.
14. Calculate model accuracy and confusion matrix.
15. Predict a new traffic situation.
16. Visualize the Decision Tree.

## Result

The Decision Tree Classification model was successfully implemented to predict traffic situations.

The following results were obtained:
- Total records: 2976
- Selected features: CarCount, BikeCount, BusCount and Total.
- Root node: Total
- Accuracy: 92.95%
- Confusion matrix was generated.
- Decision Tree visualization was generated.
- New traffic prediction: Heavy.

## Author

Shweta Koik
