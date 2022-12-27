# Neural Network Charity Analysis

### Overview:
Alphabet Soup Charity Funding is determining which charities to to invest funding in. The purpose of this project is to use deep-learning neural networks, using TensorFlow, to analyze and classify the success of charitable donations.
<br>
<BR>
  
  
<strong>I used the following methods for the analysis:</strong>
<BR>
•Data preprocessing to prepare raw data for use
<BR>
•Compiling data and splitting data for training, testing, and evaluation of the model
<br>
• Model optimization to improve the accuracy of the model
<BR>
<BR>
  
  

### Preprocessing Data
  <strong>Features of the model:</strong>
<BR>
APPLICATION_TYPE<BR> 
AFFILIATION CLASSIFICATION
<BR>USE_CASE
<BR>ORGANIZATION
<BR>STATUS
<BR>INCOME_AMT
<BR>SPECIAL_CONSIDERATIONS
<BR>ASK_AMT
<BR>
  

<strong>Target Variable:</strong> 
IS_SUCCESSFUL, showing that the charity funding was effectively used 
<BR>
<strong>Variables Removed:</strong> EIN and NAME were determined to be of no use as they will not affect the accuracy of the model
<BR>
<BR>

  
### Compiling, Training, and Evaluating the Model

<strong>Nuerons, Layers, and activation functions selected for the neural network model to attempt accuracy optimization</strong>
<BR>
<BR>
Layer 1: 60 neurons, activation: tanh, epochs: 50
<BR> 
Layer 2: 60 neurons, activation: tanh, epochs: 50
<BR>
Layer 3: 60 neurons, activation: relu, epochs: 50
<BR>
<BR>
<img src="https://github.com/meggrooms/Neural_Network_Charity_Analysis/blob/main/images/neurons_activation.png">
<BR>

  

<strong>Steps taken to try and increase model performance:</strong>
<BR>
• Using different activation types did not significantly change results, aside from the linear
<BR>
• Increasing epochs did not seem to change the result so I continued with 50
<BR>
• Changing the amount of neurons and layers did not change the outcome
<BR><BR>
  

Try 2: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid), epochs: 50 - 73% accuracy
<BR>
<img src="https://github.com/meggrooms/Neural_Network_Charity_Analysis/blob/main/images/2_attempt.png">
<BR>
  
Try 3: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid), epochs: 50 - 73% accuracy
<BR>
<img src="https://github.com/meggrooms/Neural_Network_Charity_Analysis/blob/main/images/3_attempt.png">
<BR>
  
  
Try 4: First layer 110 neurons (tanh), second layer 60 neurons (tanh), third layer 60 neurons (relu), epochs: 50 - 73% accuray
<BR>
<img src="https://github.com/meggrooms/Neural_Network_Charity_Analysis/blob/main/images/4_attempt.png">
<BR>
### Results
<BR>

