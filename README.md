# Multiple Linear Regression
## Housing Case Study

#### Problem Statement:

Consider a real estate company that has a dataset containing the prices of properties in the Delhi region. It wishes to use the data to optimise the sale prices of the properties based on important factors such as area, bedrooms, parking, etc.

Essentially, the company wants —

- To identify the variables affecting house prices, e.g. area, number of rooms, bathrooms, etc.

- To create a linear model that quantitatively relates house prices with variables such as number of rooms, area, number of bathrooms, etc.

- To know the accuracy of the model, i.e. how well these variables can predict house prices.

#### Here's the step by step approach :-

Step 1: Reading and Understanding the Data  
- Read and interpret the data using NumPy and Pandas
- Inspect the various aspects of the dataframe like it's shape, missing values and the type of data.

Step 2: Visualising the Data
- If there is some obvious multicollinearity going on, this is the first place to catch it.
- If some predictors directly have a strong association with the outcome variable it can also be easily identified.
- To visualize numeric values we can pair plot is using Seaborn sns.pairplot(df) & Matplotlib plt.show()
