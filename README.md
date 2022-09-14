# Neural_Network_Charity_Analysis
# Overview
For this project, we used deep-learning neural network with Python TensorFlow to analyze and classify the success of charitable donations. To be to perform this analysis, we used methods including: preprocessing the data for the neural network model, compile, train, and evaluate the model, and optimize the model 

# Results
### Data Preprocessing
- We removed the EIN and NAME columns from the input data.
- We used the IS_SUCCESSFUL column as our target variable for our deep learing neural network.
- We split our categorical variables into training and testing datasets.
- We applied standardization to our numerical values. 

### Compiling, Training, and Evaluating the Model 
- This deep-learning neural network model is made of two hidden layers.
- The input data has 43 features and 25,724 samples.
- The output layer is made of a unique neuron as it is a binary classification.
- We used ReLU for the hidden layers. Sigmoid is used on the output layer.
- For the compilation, the optimizer is adam and the loss function is binary_crossentropy.
- The model accuracy is under 75%, whhich was not sufficient enough to help predict the outcome of the charitable donations.
- We increased the number of neurons on one of the hidden layers, then we used a model with three hidden layers.

# Summary 
After completing this project, the deep learning neural network model did not reach the target of 75% accuracy. We made 3 attempts, and all 3 attempts fell just below the 75% target predictive accuracy. I would recommend using a supervised machine learning model such as the Random Forest Classifier. This model can combines multiple smaller models to generate a more accurate model. This model would also generate a classified output and can evaluate its performance against our deep learning model. 
