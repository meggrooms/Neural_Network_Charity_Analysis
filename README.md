# Neural Network Charity Analysis
Alphabet Soup Charity Funding
<BR>
<BR>
### Overview: (explain purpose)
<BR>
<BR>
<BR>

#### Preprocessing Data
<BR>
Variables considered the targets for the model</ins>
<BR>
<BR>
Variables considered to be the features for the model
<BR>
<Br>
Variables removed from input data as they are neither targets nor features
<BR>

  
#### Compiling, Training, and Evaluating the Model

Nuerons, Layers, and activation functions selected for the neural network model & why
<BR>
I used 3 hidden layers as following:
<BR>
<BR>
Layer 1: 60 neurons, activation: tanh
 
Layer 2: 60 neurons, activation: tanh
<BR>
Layer 3: 60 neurons, activation: relu
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
Try 1: First layer 110 neurons (relu), second layer 80 neurons(relu), third layer 80 neurons (sigmoid) - 73% accuracy
<BR>
Try 2: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid) - 73% accuracy
<BR>
Try 3: First layer 110 neurons (tanh), second layer 60 neurons (relu), third layer 60 neurons (sigmoid) - 73% accuracy
<BR>
Try 4: First layer 110 neurons (tanh), second layer 60 neurons (tanh), third layer 60 neurons (relu) - 73% accuray
