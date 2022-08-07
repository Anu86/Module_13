# Module_13
 To create binary classification model using a deep neural network to predict success of a start up if funded by Alphabet Soup Venture Capital firm.
 Implementation : 
 1. Upload the data application_data.csv to Google colab 
 2. Clean Data by identifying & encoding categorical data , scale data & add numerical columns to the & encoded dataframe
 3. Optimize model by 
     a. defining the no. of layers
     b. no. of nodees in each hidden layer
     c. try alternate with activation function
     d. adjust no. of epochs
4. We have now created 3 models 
    a. no.of hidden layers = 2 number_input_features = 116 , number_output_neurons = 1,  loss_function : binary_crossentropy, activation_function = sigmoid, epoch = 50, loss: 0.5571 - accuracy: 0.7283 
    b.  no.of hidden layers = 3 number_input_features = 116 , number_output_neurons = 1,  loss_function : binary_crossentropy, activation_function = sigmoid, epoch = 50, loss: 0.5704 - accuracy: 0.7286
    c. no.of hidden layers = 4 number_input_features = 116 , number_output_neurons = 1,  loss_function : binary_crossentropy, activation_function = sigmoid, epoch = 100, loss: 0.5589 - accuracy: 0.7312

   
Note, ideally we want loss to converge near 0 and accuracy towards 1  by increasing the layers to 4 & epoch=100 the loss decreased and accuracy increased slightly. 

     
