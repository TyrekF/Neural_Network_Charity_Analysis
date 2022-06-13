# Neural_Network_Charity_Analysis

# Overview
* Compare the differences between the traditional machine learning classification and regression models and the neural network models. Describe the perceptron model and its components. Implement neural network models using TensorFlow. Explain how different neural network structures change algorithm performance. Preprocess and construct datasets for neural network models. Compare the differences between neural network models and deep neural networks. Implement deep neural network models using TensorFlow. Save trained TensorFlow models for later use.

# Purpose
* The Alphabet Soup foundation tries to predict where to invest. The goal is to use machine learning and neural networks to add features to a dataset in order to construct a binary classifier that can predict whether or not applicants will be successful if they are sponsored by Alphabet Soup. The starting dataset contains 34,000 organizations and a number of columns including metadata from previous successful fundings.

# Results:

## Data Preprocessing
* The target variable used for this model was the "IS_Succesful" column. There were a total of twelve original features for the dataset. The columns containing the "EIN and "NAME" features did not improve the model therefore they were dropped. The other ten features were used to delevolpe the code. 
![Screenshot (183)](https://user-images.githubusercontent.com/96156893/173347638-717298f0-30fc-4161-89dc-6793eae93445.png)


## Compiling, Training, and Evaluating the Model
* For my nueral network model I used two hidden layers, one has 40 and the other has 80 neurons. I used The activation function "relu" for my two hidden layers. The output layer activation function was "linear". In my opinion they were the best fit for the model. I could not reach the target goal of 75% however The highest accuracy the model could achieve was 71.6%. Furthermore, two additional columns were dropped which were "SPECIAL_CONSIDERATIONS" and "USE_CASE". I also increased the number of hidden layers and added the linear function as well. 
![Screenshot (184)](https://user-images.githubusercontent.com/96156893/173348021-c401bb57-3fbf-4f52-880b-ebe5ba6a9750.png)


# Summary:
The optimiztion model was able to improve the models accuracy to 73%, which is the best the model could produce using various number of neurons and layers. I believe the next setp should be too continue to drop non-beneficial columns this will allow data to be smoother. After sifting through the data we could try using another model such as a random forest classifier. They are unaffected by outliners or deviation in the dataset. 
![Screenshot (181)](https://user-images.githubusercontent.com/96156893/173346659-a23fdbb5-f8df-467e-9c55-a775e97e273e.png)
