# Unsupervised-Learning---Fuel-Consumption-Prediction

Context:
The dataset focuses on predicting city-cycle fuel consumption, measured in miles per gallon (mpg), using a mix of continuous and multi-valued discrete variables. The data aims to model how various car characteristics influence fuel efficiency, providing insights into fuel consumption trends.

Data Description:
The dataset pertains to city-cycle fuel consumption (mpg) and includes various attributes describing the technical specifications and origins of different car models. These attributes fall into two categories: multi-valued discrete variables and continuous variables. The objective is to leverage these attributes to cluster the data and use the resulting clusters to build more targeted regression models for accurate mpg prediction.

Attribute Information:
mpg (Miles Per Gallon): The target variable representing fuel consumption, measured as a continuous value.
Cylinders (cyl): A multi-valued discrete attribute indicating the number of cylinders in a car's engine.
Displacement (disp): A continuous variable that measures the engine's total swept volume in cubic inches.
Horsepower (hp): A continuous variable denoting the engine's power output.
Weight (wt): A continuous attribute indicating the car's weight, typically measured in pounds.
Acceleration (acc): A continuous attribute representing the car's ability to increase speed, measured in seconds to reach a specific velocity.
Model Year (yr): A multi-valued discrete variable specifying the car's production year.
Origin: A multi-valued discrete variable indicating the car's manufacturing origin (e.g., North America, Europe, or Asia).
Car Name: A string attribute that uniquely identifies each car instance, serving as an identifier rather than a predictive feature.
Project Objective:
The primary goal of this project is to utilize clustering techniques to segment the dataset based on the similarities between car attributes. Once clustered, each group will be treated as a separate dataset to train regression models specifically tailored to its characteristics. The ultimate aim is to enhance the accuracy of predicting the city-cycle fuel consumption (mpg) for each group by building specialized regression models. This approach combines the strengths of clustering and regression to achieve a more precise prediction of fuel efficiency.
