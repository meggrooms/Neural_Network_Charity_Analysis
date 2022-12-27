# Neural Network Charity Analysis

### Overview:
Alphabet Soup Charity Funding is determining which charities to to invest funding in. The purpose of this project is to use deep-learning neural networks, using TensorFlow, to analyze and classify the success of charitable donations.
<br>
<BR>
  
  
I used the following methods for the analysis:
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

Nuerons, Layers, and activation functions selected for the neural network model to attempt accuracy optimization
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

<strong>Ability to achieve target model performance</strong>
<BR>
Target performance was 75%, the best I was able to achieve was 73%
<BR>
Steps taken to try and increase model performance:
<BR>
<BR>
Try 1: First layer 110 neurons (relu), second layer 80 neurons(relu), third layer 80 neurons (sigmoid), epochs: 50 - 73% accuracy
<BR>
Try 2: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid), epochs: 50 - 73% accuracy
<BR>
Try 3: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid), epochs: 50 - 73% accuracy
<BR>
Try 4: First layer 110 neurons (tanh), second layer 60 neurons (tanh), third layer 60 neurons (relu), epochs: 50 - 73% accuray
<BR>
<BR>
### Results
<BR>
