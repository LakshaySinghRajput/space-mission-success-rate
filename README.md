# space-mission-success-rate
This dataset predicts the success rate of space missions based on spacecraft features such as design, specifications, and launch conditions. It offers valuable insights into how various factors influence the likelihood of mission success.

This project predicts the success rate of space missions based on features like spacecraft specs and mission details. By analyzing historical mission data, we identify key factors that influence mission success, such as payload weight, mission cost, and target type.

Key Insights
Feature Selection: We focused on Payload Weight and Mission Cost, as they showed the strongest link to mission success. Launch Vehicle was removed since it didn’t impact success rates.
Target & Mission Types: Both Target Type and Mission Type showed significant variations in success, so we kept them for analysis.
Correlations: Mission Duration was dropped due to its high correlation with Fuel Consumption, which we kept in the model.
Approach
Data Preprocessing: Cleaned the dataset by removing irrelevant columns and handling missing data. Features with weak correlations were dropped.
Modeling: We used AdaBoost regression to predict the mission success rate, focusing on the most influential features.
Feature Engineering: Transformed numerical data to improve model accuracy.
