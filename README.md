# Neural_Network_Charity_Analysis
### Neural Network and Deep Learning

## Overview of the analysis
The analysis is about using machine Learning and neural network knowledge and the features provided dataset to help Beks create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup. Alphabet Soup’s business team provided a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years.

## Project Deliverables:
1.	Preprocessing Data for a Neural Network Model
2.	Compile, Train, and Evaluate the Model
3.	Optimize the Model
4.	A Written Report on the Neural Network Model

## Results

#### Data Preprocessing

1. For this model , the target is the binary feature ‘IS_SUCCESSFUL’. It shows whether the fund was used effectively.

2. The features for the model are the following columns "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION", "USE_CASE", "ORGANIZATION", "INCOME_AMT", "SPECIAL_CONSIDERATIONS", "ASK_AMT", "STATUS"

3. “EIN” and “NAME” are identification columns, they are neither targets nor features and was removed from the input data

#### Compiling, Training, and Evaluating the Model

1. How many neurons, layers, and activation functions did you select for your neural network model, and why?

2. The model performance is about 73% which below theTtarget Model performance which is 75%


## Summary
In summary, the deep learning model result is about 73% approximately. Several other methods were utilized to optimize the performance, the result did not exceed the target model performance of 75%.
I will recommend on using the Random Forest Model, which is a different model to solve the classification problem, and justification. Random Forest Model is able to achieve comparable predictive accuracy on large tubular data with less code and faster performance.
