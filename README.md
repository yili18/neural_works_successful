# Deep Neural Network Model for Binary Classification

## This project is to predict the success of Alphabet Soup–funded startups based on various features provided in the dataset.

* Prepare the data for use on a neural network model.
  * Read the "applicants_data.csv" file into a Pandas DataFrame using the `read_csv()` function.
  * Drop the irrelevant columns ("EIN" and "NAME") from the DataFrame using the `drop()` function.
  * Encode the categorical variables using the `OneHotEncoder` from `scikit-learn`, and store the encoded variables in a new DataFrame.
  * Concatenate the original numerical variables with the encoded variables DataFrame using the `concat()` function.
  * Split the dataset into `features (X)` and `target (y)` datasets based on the preprocessed DataFrame, where the target variable is defined by the "IS_SUCCESSFUL" column.
  * Scale the features data using the `StandardScaler` from `scikit-learn`.

* Compile and evaluate a binary classification model using a neural network.
  * Design a deep neural network model using `TensorFlow/Keras`, specifying the number of input features, layers, and neurons per layer.
  * Compile the model using the `compile()` function, specifying the `binary_crossentropy loss function`, the `adam optimizer`, and the `accuracy evaluation metric`.
  * Fit the model on the training data using the `fit()` function.
  * Evaluate the model's performance on the test data using the `evaluate()` function, calculating the `loss` and `accuracy` metrics.
  * Save and export the model to an HDF5 file using the `save()` function, naming the file `"AlphabetSoup.h5"`.

* Optimize the neural network model.
  * Define at least two new deep neural network models with modifications aimed at improving accuracy.
  * Compare the accuracy scores achieved by each model and analyze the results.
  * Save each optimized model as an HDF5 file.
 
