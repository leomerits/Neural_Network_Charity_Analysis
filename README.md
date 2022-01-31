# Neural_Network_Charity_Analysis
# Overview of the analysis:
In this module we explored and implemented neural networks using the TensorFlow platform in Python.
# Resources: 
- Data Source: charity_data, AlphabetSoupCharity, AlphabetSoupCharity_Optimzation
- Software: Jupyter Notebook.
# Results:
## Data Preprocessing
- Target Variables in my modudle is the  IS_SUCCESSFUL Column
- Features for Model Variable in my model are every Column except for IS_SUCCESSFUL which is our target and the ones we will drop
- Variables that are neither targets nor features that should be removed are are EIN, NAME because they will have little to no impact om our outcome

## Compiling, Training, and Evaluating the Model
- I selected 2 hidden layers, the first layer had 80 neurons, the second has 30 and an output layer. The first and second hidden layer have the "relu" activation function and the activation function for the output layer is "sigmoid."

![image](https://user-images.githubusercontent.com/34757498/151729727-509009ff-4bf6-4930-890a-6a6d3cea467d.png)

- Achieved the target model?: No the model was not able to achieve the target model performance.
Attempt1:

![Loss_Accuracy_1](https://user-images.githubusercontent.com/34757498/151644960-bfa6df4a-7329-4424-a1ef-a7aa26364ed2.png)

- Steps to try and increase nodel performance: I tried two more attempts increasing the nodes so as to increase model perfomance.
Attempt2:

![Loss_Accuracy_2](https://user-images.githubusercontent.com/34757498/151644981-cc74991f-5717-43ca-8a03-a2776d48ff72.png)

Attempt3:

![Loss_Accuracy_3](https://user-images.githubusercontent.com/34757498/151644994-478ea5d2-12e3-48f0-8c5d-e0f5c0e439cd.png)

# Summary: 
By the end of the module we were able to:
- Compare the differences between the traditional machine learning classification and regression models and the neural network models.
- Describe the perceptron model and its components
- Implement neural network models using TensorFlow.
- Explain how different neural network structures change algorithm performance.
- Preprocess and construct datasets for neural network models.
- Compare the differences between neural network models and deep neural networks.
- Implement deep neural network models using TensorFlow.
- Save trained TensorFlow models for later use.
