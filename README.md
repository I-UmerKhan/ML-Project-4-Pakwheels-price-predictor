# ML Project 4 Pakwheels price predictor
 
PakWheels is a leading automotive website in Pakistan, offering a comprehensive platform for buying, selling, and researching cars. In my PakWheels price predictor project, I first focused on preprocessing the data. This involved cleaning the dataset by removing non-numerical values from numerical features, eliminating unwanted characters, and handling null values. I also extracted the first three words from each row of the name feature for better categorization.

After preprocessing, I conducted exploratory data analysis (EDA) to gain insights into the data and identify any patterns or trends. This step was crucial in understanding the relationships between different features and the target variable, which in this case was the car price.

Next, I evaluated the performance of various models, including XGBoost, linear regression, and random forest. Each model was tested to determine its accuracy and predictive power. Among these, the random forest model demonstrated the best performance in terms of accuracy and reliability. As a result, I selected the random forest model to predict car prices based on the provided features.

The final model was deployed to predict the price of a car, leveraging the comprehensive feature set from the dataset. This project showcases the effectiveness of machine learning in making accurate predictions and highlights the potential of using advanced models like random forest in real-world applications.
