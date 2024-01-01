

```markdown
# Neural Network Classification for Dependent Variable Prediction

This project utilizes a neural network for classification tasks to predict a dependent variable. The neural network is implemented using the Keras library and trained on a dataset called `dep_clean.csv`. The project includes data analysis, model training, evaluation, and prediction steps.

## Description
The main objective of this project is to build and train a neural network model to predict a dependent variable based on a set of input features. The project follows these steps:

1. Data Analysis: The `dep_clean.csv` dataset is loaded using pandas. The project includes a heatmap visualization using seaborn to analyze the correlations between the features.

2. Model Training: The project utilizes the Keras library to build a neural network model. The model consists of two dense layers with ReLU activation functions and a final dense layer with a sigmoid activation function. The model is compiled with the Adam optimizer and trained on the training dataset.

3. Model Evaluation: The performance of the model is evaluated using the training and testing datasets. The project calculates and displays the training and testing accuracy scores.

4. Prediction: The trained model is used to make predictions on new data. An example prediction is provided using a sample input data point (`man`), and the prediction probabilities are visualized using a bar plot.

## Usage
To use this project, follow these steps:

1. Clone the repository:
   ```shell
   git clone https://github.com/Yasamin-Alemzadeh/NeuralNetwork-Classification-Dep
   ```

2. Install the required dependencies. You can use the following command to install them:
   ````shell
   pip install numpy pandas seaborn matplotlib tensorflow keras
   ```

3. Open the project in a Python environment or a Jupyter Notebook.

4. Run the code cells sequentially to reproduce the data analysis, model training, evaluation, and prediction steps.

## Dependencies
The project requires the following dependencies:

- numpy
- pandas
- seaborn
- matplotlib
- tensorflow
- keras

Make sure to install these dependencies using pip or any other package manager before running the project.

```
