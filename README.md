# Estimating-2nd-hand-Laptop-Price
Business objective:A C2B firm is in the process of creating an online platform where the consumers can sell their used laptops. This platform should host an automated mechanism that can suggest to a consumer the realistic price of their used laptop when the required details (different features of the laptop) are provided.

Understanding:A firm whose business nature is of the type consumer to business(C2B) wants to introduce an automated mechanism such that consumer who wants to sell their laptop has to fill the features of the laptop in order to get the reasonable price of their laptop.

Approach:The first step involves the cleaning of the given data which includes identifying missing values ,checking duplicate rows and dropping unnecessary columns.
The next step is data preprocessing which involves exploratory data analysis and feature engineering.
As the given dependent variable is a continuous variable, we are using decision tree regression algorithm.
If any overfitting occurs we need to prune the decision tree using hyperparameters and right set of hyperparameters can be achieved by using a method called GridsearchCV.





