# Neural_Network_Charity_Analysis

## OVERVIEW

The purpose of this analysis is to take a list of 34,000 foundations and use neural network machine learning in order to predict where the best investment opporunities would be.


## RESULTS

### Data Processing
- The variable being used is tracking whether or not the foundation is successful.
- The features of this data set are the foundations application type, affiliation, classification, use case, organization, status, income amt, special considerations, and their asking amount.
- For this machine learning model, the EIN ID # and the name of the foundations have been removed.</br>
![image](https://user-images.githubusercontent.com/102704559/185723326-50d8e3d2-b90e-42ad-9abd-048523f55d29.png)


### Compiling, Training, and Evaluating the Model

- The model used 2 layers with 10 and 5 neurons respectively, using the ReLU function for hidden layers and Sigmoid function for the output layer. The 2 layers were chosen to avoid overfitting, and when attempting optimization with 3 and 4 layers, there was little to no improvement in the accuracy of the model.
- The target for this model was a 75% accuracy score; despite multiple attempts to optimize and increase this score the maximum accuracy achieved was 72%
- Some steps taken to try and increase performance were: increasing layers, increasing neurons, adding back in the name values, and switching the activation function from ReLU to Tanh.</br>

![image](https://user-images.githubusercontent.com/102704559/185723451-3ebedf46-284b-4330-bb91-e94b8e0aebc2.png)

## SUMMARY

This model remained relatively close to the desired accuracy score with a 72% out of 75%, however, the loss rate for the model remains relatively high at 0.556. Since this is a binary classification situation, the Random Forest Classifier could be used to combine multiple decision trees to generate an output and evaluate performance against the deep learning model.
