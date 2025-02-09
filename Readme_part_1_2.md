# In Part 1 you will learn topic like
#### 1: Univariate
#### 2: bivariate
#### 3: Standardization 
#### 4: Normalization
#### 5: Ordinal Encoding
#### 6: Label Encoding
#### 7: OneHot Encoding
#### 8: Column Transformer


## Univariate Analysis

Univariate analysis involves the examination of a single variable. The purpose of univariate analysis is to describe the data and find patterns that exist within it. This type of analysis can be performed using various statistical measures such as mean, median, mode, range, variance, and standard deviation.

### Uses
- Summarizing data
- Identifying patterns
- Detecting outliers
- Understanding the distribution of data

### Benefits
- Simplifies complex data sets
- Helps in making informed decisions
- Provides a clear understanding of the variable's behavior

## Bivariate Analysis

Bivariate analysis involves the examination of two variables simultaneously to determine the empirical relationship between them. This type of analysis can be performed using scatter plots, correlation coefficients, and regression analysis.

### Uses
- Identifying relationships between variables
- Predicting one variable based on another
- Testing hypotheses

### Benefits
- Helps in understanding the interaction between variables
- Aids in predictive modeling
- Provides insights into cause-and-effect relationships

## Standardization

Standardization involves rescaling the features of your data so that they have a mean of 0 and a standard deviation of 1. This is particularly useful when the data has different units or scales.

### Uses
- Preparing data for machine learning algorithms
- Ensuring features contribute equally to the analysis
- Improving the performance of gradient descent

### Benefits
- Reduces the impact of outliers
- Speeds up convergence in optimization algorithms
- Enhances the interpretability of coefficients in regression models

### We apply on algorithams like 
- K-Means
- Gradiant Descent
- Principle component analysis
- Artificial Neural Network

## MinMax Scalar

## Normalization

Normalization involves rescaling the features of your data to a range of [0, 1] or [-1, 1]. This is useful when you want to ensure that all features contribute equally to the analysis.

### Uses
- Preparing data for machine learning algorithms
- Ensuring features contribute equally to the analysis
- Improving the performance of distance-based algorithms

### Benefits
- Reduces the impact of outliers
- Enhances the interpretability of coefficients in regression models
- Improves the performance of algorithms that rely on distance metrics

## Ordinal Encoding

Ordinal encoding involves converting categorical data into numerical data by assigning a unique integer to each category. This is useful when the categories have a meaningful order.

### Uses
- Preparing data for machine learning algorithms
- Handling ordinal categorical data
- Simplifying the representation of categorical variables

### Benefits
- Preserves the order of categories
- Reduces the dimensionality of the data
- Enhances the interpretability of the model

## Label Encoding

Label encoding involves converting categorical data into numerical data by assigning a unique integer to each category. This is useful when the categories do not have a meaningful order.

### Uses
- Preparing data for machine learning algorithms
- Handling nominal categorical data
- Simplifying the representation of categorical variables

### Benefits
- Reduces the dimensionality of the data
- Enhances the interpretability of the model
- Facilitates the use of categorical data in machine learning algorithms

## OneHot Encoding

OneHot encoding involves converting categorical data into binary vectors, where each category is represented by a unique binary vector. This is useful when the categories do not have a meaningful order and you want to avoid introducing ordinal relationships.

### Uses
- Preparing data for machine learning algorithms
- Handling nominal categorical data
- Simplifying the representation of categorical variables

### Benefits
- Avoids introducing ordinal relationships
- Preserves the information in categorical variables
- Facilitates the use of categorical data in machine learning algorithms

## Column Transformer

A column transformer allows you to apply different preprocessing steps to different columns of your data. This is useful when you have a mix of numerical and categorical data that require different preprocessing steps.

### Uses
- Preparing data for machine learning algorithms
- Handling mixed data types
- Simplifying the preprocessing pipeline

### Benefits
- Streamlines the preprocessing workflow
- Ensures consistent preprocessing across columns
- Enhances the flexibility of the preprocessing pipeline