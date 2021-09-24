# nlp
#### What is a neural network neuron?

It's basic or fundamental unit of Neural Networks. It constitutes of inputs, parameters, output and activation function.
1. Inputs : They are fed into Neuron
2. Activation Function : Activation function makes derivation involved in back propogation easy. Sigmoid, tanh, Soft Max etc are some most commnly used activation functions. 
3. Weights or Parameters : They are multiplied with Inputs( similar vector multiplication) which then becomes input for activation function. Weights are intialized to random normalized values. They are fine tuned to reduce prediction error.
4. Ouput : Either they are feed to other neurons or final Outputs themselves.

Complex Non Linear relation between Inputs & Outputs will be captured by the neurons activation function & their inter weaving(connectivity). 
 

#### What is the use of the learning rate?

Learning rate is a key component of back propogation partial differentition in a Nueral Network. A parameter is updated based on learning rate & prediction error. Learning rate helps in convergence of prediction error to local minimum. Learning rate can be constant(like Linear regression) or variable at each epoch. If a big learning rate is choosen our parameters never converge to optimal values as they oscillate. If a small learning rate is choosen our parameters take long time to converge to optimal values. Hence an optimal value should be choosed. 

#### How are weights initialized?

Weights or Parameters can be initialized to random values. But just to save time with convergence, better to pick weights between a range which is normalized. Picking between this range avoids weight saturation also. 

#### What is "loss" in a neural network?

Loss is function of predicted output, expected ouput. This captures how far our prediction is from actual value. Most commonly used error is Root Mean Square Error (RMSE). Loss helps to model neural network problem as optimization problem. 

#### What is the "chain rule" in gradient flow?

Chain Rule is a derivation technique. Since we have activation function at neuron, chain rule comes handy. When differentiating error which constitutes of activation function this rule make things simple.  

#### Assignment
We have 2 Hidden layers. 

First Hidden Layer has 5 nuerons.

Second Hidden Layer has 4 nuerons. 

First set of parameters will be 3x5 which is between input & first hidden layer.

Second set of parameters will be 6x4 which is between 1st hidden layer & 2nd hidden layer.

Third set of parameters will be 5x1 which is between 2nd hidden & output. 

### Team :

T R K Saran

Shyamant Achar

Shaan Respwal
