# Credit Analysis Study

This project aims to use artificial intelligence and machine learning techniques to analyze credit data and predict credit risk.

### Installation
To use this project, you will need to have Python 3.8 or higher and the following libraries installed:

- NumPy

- Pandas

- Matplolib
 
- Seaborn

- Scikit-learn

- TensorFlow 

You can install these libraries using pip:

`pip install numpy pandas matplotlib seaborn scikit-learn tensorflow`

### Usage
You can use the provided Jupyter notebooks to explore the data and train machine learning models. [code.ipynb](https://github.com/bernardoavsouza/credit-analysis/blob/main/code.ipynb) notebook contains an example of how to train a neural network with TensorFlow to predict credit risk.

### Data
The data used in this project is provided by the [UCI](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data)). It consists of loan data from a german company, including categorical and numerical information.


### Overview

- Preprocessing:

The feature vector aims to simplify the model as much as it can. 
Since the dataset chosen is skewed, a data augmentation methodology was implemented to mitigate this issue. To do so, SMOTE algorithm was used to match the amount of sample of each class.


- Validaton Method:

The validation method chosen for this project was Train-Validation-Test separation, which is 64%, 16%, and 20% of the whole data, respectively.


- Neural Network Structure:

The neural network implemented has 15 neurons on the input layer, and the second layer is the output one where there is a single neuron.


- Regularization:

To avoid overfitting, an L2 regularization was implemented with L2 = 0.016.


- Results:

The overall result of this intelligence is a precision score of 80% and an F1-score of 78%.


### Credits
The code used in this project was developed by [Bernardo A V de Souza](https://www.linkedin.com/in/bernardoavsouza/)
