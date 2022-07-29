# **Linear Regressions with L2/Ridge Regularization**
## Project Description
This project takes 6 datasets and implements L2-Regularized Multple Linear Regression algorithm for all rows of X as a function of Y with Lambda values ranging from 0 to 150.

The datasets each have multiple features and rows/observations. We use feature matrixes (X) and a response vector (Y). The regression line is a function of the two. The assignment also plot the Mean Square Errors for the training and test data as a function of Lambda. The third questions asks to run a 10 Fold Cross Validation to find the best choice Lambda based on Mean Square Errors. Finally we plot a Learning Curve for Lambda as 1, 25 and 100. 
 
## Operating Environment
Python 3.9.6 64-bit // Jupyter Notebooks

## Implementation and Execution
1. Open up your virtual environment, Jupyter Notebooks and select a Python interpreter. 
2. Change working directory to the folder where `devika_chandnani_CS5790_HW2.ipynb` and the folder `data` are stored.
3. The project requires **Pandas**, **Numpy**, **Matplotlib**, **Operator** and **Random** libraries, the first block of code imports them.
4. Run all following lines. 

## Output

The first block of code is responsible for creating 3 additional files:
1. `train-50(1000)-100.csv`
2. `train-100(1000)- 100.csv`
3. `train-150(1000)-100.csv`

Running the rest of the code will output files `Ans_Question2.pdf` which is a pdf file of 6 subplots, each displaying the Training Set and Test Set Mean Square Error. The next output file is `Ans_Question2B.pdf` which is a subplot of 3 graphs displaying the Training Set and Test Set Mean Square Error with Lalmbda starting at 1 instead of 0. `Ans_Question4.pdf` results in a subplot including 3 learning curves at Lambda 1, 25 and 150.


