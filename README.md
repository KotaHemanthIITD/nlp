# nlp
What is a neural network neuron?
It's basic or fundamental unit of Neural Networks. It constitutes of inputs, parameters, output and activation function.
1. Inputs : They are feeded into Neuron
2. Activation Function : Activation function is makes derivation involved in back propogation easy. Sigmoid, tanh, Soft Max etc are some most commnly used activation functions. 
3. Weights or Parameters : They are multiplied with Inputs( similar vector multiplication) which are input for activation function. Weights are intialized to random normalized values. They are fine tuned to reduce prediction error.
4. Ouput : Either they are feed to other neurons or final Outputs themselves.
Complex Non Linearity relation between Inputs & Output will be captured by the neurons activation function & inter linking. 
 

What is the use of the learning rate?
It's a key component of back propogation partial differentition in a Nueral Network. A parameter is update based on learning rate & prediction error. Learning rate helps in converging the prediction error to local minimum. Learning rate can be constant(like Linear regression) or variable at each epoch. If a big learning rate is choosen our parameters never converge to optimal values as they oscillate. If a small learning rate is choosen our parameters take long time to converge to optimal values. Hence an optimal value should be choosed. 

How are weights initialized?
Weights or Parameters can be initialized to random values. But just to save time with convergence, better to pick weights between a range which is normalized. Picking between this range avoids weight saturation. 

What is "loss" in a neural network?
Loss is function of preducted output, expected ouput. This captures how far our prediction is from actual value. Most commonly used error is Root Mean Square Error (RMSE). Loss helps to model neural network problem as optimization problem. 

What is the "chain rule" in gradient flow?
Chain Rule is a derivation technique. Since we have activation function at neuron, chain rule comes handy. When differentiating error which constitutes of activation function this rule make things simple.  
