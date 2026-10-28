# Smart Electricity Consumption Prediction Using Machine Learning and Ensemble Regression

## Course Details
- **Course:** CS3201T: Machine Learning Mini Project
- **Project Category:** Supervised Algorithm (Regression & Ensemble Learning)

## Dataset Details
- **Dataset Name:** Individual Household Electric Power Consumption Dataset (UCI Machine Learning Repository)
- **Description:** Contains household electricity consumption measurements including Date, Time, Global Active Power, Global Reactive Power, Voltage, Global Intensity, and Sub-metering (1, 2, and 3).

## Machine Learning Pipeline Implemented
1. **Data Preprocessing:** Handled missing records and formatted date/time series strings.
2. **Feature Engineering:** Extracted temporal features (`Hour`, `DayOfWeek`, `Is_Weekend`) and combined appliance sub-metering (`Total_Sub_Metering`), followed by feature scaling via `StandardScaler`.
3. **Model Building:**
   - **Baseline Model:** Multiple Linear Regression
   - **Ensemble Models:** Random Forest Regressor (Bagging), AdaBoost Regressor, and Gradient Boosting Regressor (Boosting)
4. **Evaluation Metrics:** Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and $R^2$ Score.
