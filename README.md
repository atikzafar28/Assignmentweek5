In this project, I worked on the Kaggle House Prices dataset to predict home sale prices. I combined the training and test sets for consistent preprocessing.

The target variable SalePrice was log-transformed to reduce skewness. Missing values were handled smartly—using the mode for categorical features, the median for numerical ones, and 'None' for features representing absence.

Ordinal features like quality ratings were label-encoded, and nominal categories were one-hot encoded. I also converted features like MSSubClass, MoSold, and YrSold to strings and standardized numerical features with StandardScaler.

I included helpful visualizations—such as distribution plots, missing value charts, and correlation bars—to guide decisions.
