# road-accident-severity-model
a linear regression model for analyzing road accident severity using the relevant dataset related to the scenario.

Data Preparation

Since my original dataform did not have numerical values, i opted to mapp the values and create a numerical file to make my data easier to work with. I successfully loaded the dataset and performed necessary mappings for categorical variables (e.g., Day_of_week, Sex_of_driver, Light_conditions, etc.). Then handled missing values by filling them with appropriate placeholders.

Model Training:

I created a linear regression model using relevant independent variables (Driving_experience, Road_surface_conditions, Weather_conditions, Light_conditions, Day_of_week) then split the dataset into training and testing sets using train_test_split.
Then trained the model and printed the intercept and coefficients.

Model Evaluation:

I calculated evaluation metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) and this were the values i got [mean absolute error 0.2788046662370771, mean squared error 0.2788046662370771, Root mean squared error 0.5280195699375896] which indicate that while the model provides reasonable predictions of accident severity, there is still room for improvement in its accuracy.

I saved the trained model using joblib for future use and  created a diverse testing array to predict accident severity based on hypothetical scenarios.

BENEFITS OF MODEL

1.Informed Decision-Making:

  Policymakers can use insights from the model to make data-driven decisions regarding road safety measures, such as improving signage or enhancing road conditions in high-risk areas.
  
2.Targeted Interventions:

  The model can help identify high-risk conditions (e.g., specific weather conditions or times of day) that lead to severe accidents, guiding targeted interventions like increased police presence or public awareness campaigns during those times.

3.Resource Allocation:

  Understanding which factors contribute most significantly to severe accidents allows authorities to allocate resources more effectively, focusing on areas that need the most attention.

4.Predictive Analytics:

  The ability to predict accident severity based on real-time data inputs can enhance traffic management systems, enabling proactive measures to prevent accidents before they occur.

5.Improved Road Infrastructure:

  Analyzing accident data can highlight areas where infrastructure improvements are needed (e.g., better lighting in high-accident zones), leading to safer roads overall.

6.Public Awareness:

  Sharing insights from the model with the community can raise awareness about safe driving practices and the importance of adhering to traffic regulations.

7.Training Programs:

  Insights from the model can inform driver training programs by emphasizing conditions that lead to higher accident severity, thereby improving driver education.


