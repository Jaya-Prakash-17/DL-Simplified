## Payment Fraud Detection using Deep Learning

### 🎯 Goal:
###### Creating a DL project to detect any fraud in the online payments/transactions to secure the bank and users.

### 🧵 Dataset:
https://www.kaggle.com/datasets/ealaxi/paysim1

###### The dataset comprises of total 6362620 transactions. This synthetic dataset is scaled down 1/4 of the original dataset. Remember that Transactions which are detected as fraud are cancelled.

### 🧾 Description:
###### This project aims to develop a model capable of accurately detecting the fraudlent payments out the log provided. The dataset is used for training, validating and testing the models to achieve the most precise accuracy.

### What I had done:
###### 1. **Data Preprocessing:**
######   - Load and explore the dataset.
######   - Exploratory Data Analysis.
######   - Data Visualization

###### 2. **Train-Test Split:**
######   - Split the dataset into train, validate and test. (4072076 train examples, 1018020 validation examples, 1272524 test examples)

###### 3. **Model Training (after data pipelining) :**
######   - Single Neural Network
######   - Multi-input Neural Network.
######   - Recurrent Neural Network (LSTM Model).

###### 4. **Evaluation:**
######   - Assess model performance on the test set.
######   - Analyze and interpret the results.

### Models used:
###### Single-input Neural Network Model:
###### Only one input layer is used to process the data. All features are combined into a single input layer (feature_layer), which is then fed into the sequential model. This approach is suitable when all features are of the same type and have a similar representation in the network.
###### Multi-input Neural Network Model:
###### Utilizes multiple input layers to handle different types of data. Each input layer processes a specific type of data or feature. The outputs of these input layers are then combined or merged before passing through the sequential model.This approach is beneficial when dealing with heterogeneous data types or when different features require different preprocessing steps.
###### Recurrent Neural Network (Long short term memory Model):
###### Particularly effective for tasks involving sequential data, where the model needs to remember information from previous time steps or tokens.

### Libraries needed:
###### pandas
###### numpy
###### matplotlib
###### scikit-learn
###### tensorflow
###### keras

### Visualizations:
###### Correlation Matrix-
![Correlation Matrix](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/4c3cb44b-6054-4c7a-8d19-99eaa605e212)
###### Count of all type of transaction
![Count of all type of transaction](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/46733b4b-3d1b-49b5-a900-6318f38716f3)
###### Count of frauds
![Count of frauds](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/a31cc303-59a4-4612-8fba-4e6d6fa4f12c)
###### Number of transaction by Type of transaction and isFlaggedFraud
![Number of transaction by Type of transaction and isFlaggedFraud](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/283bfaff-919e-4f3e-8c02-966ea8f2775c)
###### Number of transaction by Type of transaction and isFraud
![Number of transaction by Type of transaction and isFraud](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/bd944358-592e-4b17-928d-58742e78114b)


### Conclusion: 
###### After traing and testing model the accuracies we got are upto 99.93% (yet at first epochs, can do for more epochs but alot time is required)

### Accuracy Table:
![image](https://github.com/AgrawalTitiksha/DL-Simplified/assets/117917014/6b34209f-8f3e-4bd0-8009-09e2416029be)

### Contributor:
###### Name: Titiksha Agrawal
###### linkedin: 
https://www.linkedin.com/in/titiksha-agrawal-056004251/
###### github:
https://github.com/AgrawalTitiksha
