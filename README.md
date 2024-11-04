# Automobile-Fuel-Efficiency-Analysis
![image](https://github.com/user-attachments/assets/774b5842-c400-43ce-9e61-b4cf5c23f17e)


## Project Overview
This project aims to predict the miles per gallon (MPG) of various car models using the `mtcars` dataset. We explore the relationships between different car attributes, visualize the data, and build a linear regression model to predict MPG.

## Dataset
The `mtcars` dataset comprises specifications and performance measurements for 32 different car models. Key variables in the dataset include:

- `mpg`: Miles per gallon
- `cyl`: Number of cylinders
- `disp`: Displacement (cu.in.)
- `hp`: Horsepower
- `drat`: Rear axle ratio
- `wt`: Weight (1000 lbs)
- `qsec`: 1/4 mile time
- `vs`: V/S (0 = V-shaped, 1 = straight)
- `am`: Transmission (0 = automatic, 1 = manual)
- `gear`: Number of forward gears
- `carb`: Number of carburetors

## Key Steps
1. **Data Exploration**: Analyzed the dataset using summary statistics and visualizations to understand the distributions and relationships among variables.
2. **Data Cleaning**: Checked for missing values and converted relevant columns to factors.
3. **Visualization**: Created various plots, including:
   - Bubble plot of MPG vs. horsepower
   - Boxplots of MPG by transmission type
   - Correlation heatmap to identify relationships among variables
4. **Model Building**: Developed a linear regression model using `hp`, `wt`, and `cyl` as predictor variables for MPG.
5. **Model Evaluation**: Evaluated the model performance using Root Mean Square Error (RMSE) and visualized actual vs. predicted MPG values.

## Conclusion
This project analyzes the mtcars dataset to predict miles per gallon (MPG) based on various car attributes. Through exploratory data analysis and linear regression modeling, we identified significant factors such as horsepower and weight that influence MPG. The model showed reasonable predictive accuracy, as demonstrated by the RMSE and residual analysis. Future work could involve applying more advanced modeling techniques to enhance predictions and exploring additional datasets for a broader analysis of car performance.

