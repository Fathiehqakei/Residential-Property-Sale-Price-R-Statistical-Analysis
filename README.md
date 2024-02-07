The aim of the project is to analyze the factors influencing the sale price of residential properties using a dataset focused on house sales in Ames, Iowa. The study begins with an overview of the real estate market's complexity and the significance of various factors like location, property size, and structural attributes in determining property values. The dataset used for analysis, named sahp, is built under r02pro package in R statistical software version 4.3.1. It is a subset of the larger Ames housing dataset; it contains 165 observations and 12 predictor variables, including the sale price as the dependent variable.

The study's primary objective is to identify which features of a house have the most significant impact on its sale price. To achieve this, the project employs a multiple linear regression model. The model includes predictor variables such as the number of bedrooms, bathrooms, garage capacity, overall material and finish quality, living area square footage, lot area, kitchen quality, and heating quality. Categorical variables are handled using one-hot encoding, and the date of sale is partitioned into separate columns for day, month, and year.

After preliminary model building and variable selection, a final model is derived, focusing on the most influential predictor variables. The results indicate that the number of bathrooms has the most significant influence on the sale price, followed by overall quality and finish material and garage car capacity. Other variables like the number of bedrooms, living area square footage, lot area, kitchen quality, and heating quality have a lower impact on the sale price. Surprisingly, variables such as sale date, house style, and the presence of central air conditioning have no significant influence on the sale price.

The project concludes by discussing the implications of the findings and acknowledging potential limitations, such as the dataset's size and scope. Despite these limitations, the analysis provides valuable insights into the factors driving residential property prices in the Ames area.
