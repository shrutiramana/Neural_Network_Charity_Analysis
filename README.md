# Neural_Network_Charity_Analysis

### Overview of the analysis:
The purpose of this analysis is to use the given data containing 34,000 organizations that have received funding from Alphabet Soup. For this purpose deep-learning neural networks with the TensorFlow so we can analyze charitable donations.Following Analysis was done:

- Preprocessing the data for the neural network model.
- Compile, train and evaluate the model.
- Optimize the model.

### Results 

 * Data Preprocessing

    1. What variable(s) are considered the target(s) for your model?
       From the dataset IS_SUCCESSFUL is considered as the target for our deep learning neural network.
       
       <img width="1085" alt="image" src="https://user-images.githubusercontent.com/98556229/187007756-730ed868-bf5e-4bd4-b72a-492f29007ef0.png">
       <img width="1008" alt="image" src="https://user-images.githubusercontent.com/98556229/187007767-cd88c110-98ae-4023-91d2-c92f1bb02bfa.png">
       <img width="667" alt="image" src="https://user-images.githubusercontent.com/98556229/187007777-de854dc0-7f7a-4d87-a733-23e5973d9405.png">
       <img width="983" alt="image" src="https://user-images.githubusercontent.com/98556229/187007790-367935d4-ee8a-40d2-a99f-1c042b14f71e.png">
       <img width="1007" alt="image" src="https://user-images.githubusercontent.com/98556229/187007800-762f689a-e364-4694-95de-7210b7e618bd.png">

       

       
    2. What variable(s) are considered to be the features for your model?
    
       From the dataset APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS,
       INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT.

    3. What variable(s) are neither targets nor features, and should be removed from the input data?
       EIN and NAME are neither targets nor featurs so we drop it from the dataframe.
       
       
 * Compiling, Training, and Evaluating the Model
 
    1. How many neurons, layers, and activation functions did you select for your neural network model, and why?
    <img width="1030" alt="image" src="https://user-images.githubusercontent.com/98556229/187008129-db135412-c112-4f0d-97f1-9f536673b70b.png">
      * number_input_features = len(X_train[0])
      * hidden_nodes_layer1 = 80
      * hidden_nodes_layer2 = 30
      * Activation layer = "relu"

    
    2. Were you able to achieve the target model performance?
     * Model accuracy - Accuracy: 0.691428542137146. No we were not able to achieve Accuracy of over 75% , we tried to add more/less hidden layers. We  
     changed the number of neurons to change the performance.
     
     <img width="1138" alt="image" src="https://user-images.githubusercontent.com/98556229/187008233-bb37c3ba-1b06-4734-8e3d-7bbf450fc877.png">

    
    3. What steps did you take to try and increase model performance?
    <img width="1042" alt="image" src="https://user-images.githubusercontent.com/98556229/187008277-85218c6d-cb04-494c-857a-7a1df75ab234.png">
    <img width="1025" alt="image" src="https://user-images.githubusercontent.com/98556229/187008282-132d55bf-8e47-4ebe-8d9a-bc7ddc1f3f30.png">
    
    <img width="1029" alt="image" src="https://user-images.githubusercontent.com/98556229/187008299-a3524818-9843-431e-97fb-9e2ff662b8e5.png">
    <img width="1003" alt="image" src="https://user-images.githubusercontent.com/98556229/187008342-9a0b21e6-ad04-4e0b-ae84-acec9d5001ea.png">

    <img width="974" alt="image" src="https://user-images.githubusercontent.com/98556229/187008350-ac0608a8-b014-41b2-ae34-f19acc42a7d7.png">
    <img width="938" alt="image" src="https://user-images.githubusercontent.com/98556229/187008367-a7ca386b-d148-415d-9c30-8e8ebb69befe.png">
    
    
    ### Summary 
    The Accuracy that we were able to achieve 72.5% the best produced result, using various number of neurons and layers as indicated in attempt 3 shown above.May be we can try to do some other classification models so as to compare it's performance.


    

