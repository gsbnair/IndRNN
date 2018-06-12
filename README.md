# Independently Recurrent Neural Network (IndRNN): Building A Longer and Deeper RNN

Independently Recurring Neural Network

Recurrent neural networks (RNNs) have been widely used for processing sequential data. However, RNNs are commonly difficult to train due to the well-known gradient vanishing and exploding problems and hard to learn long-term patterns. Long short-term memory (LSTM) and gated recurrent unit (GRU) were developed to address these problems, but the use of hyperbolic tangent and the sigmoid action functions results in gradient decay over layers. Consequently, construction of an efficiently trainable deep network is challenging.

In addition, all the neurons in an RNN layer are entangled together and their behaviour is hard to interpret. To address these problems, a new type of RNN, referred to as independently recurrent neural network (IndRNN), is proposed in this paper, where neurons in the same layer are independent of each other and they are connected across layers. 

Experimental results have shown that the proposed IndRNN is able to process very long sequences (over 5000 time steps), can be used to construct very deep networks (21 layers used in the experiment) and still be trained robustly.

In this project, you can find few solutions developed using IndRNN.

> NOTE: As mentioned above, the desired results can be achieved only if you have the patience to run over 5000 time steps. 

If you are in search of a *robust solution* and have the time and infrastructure, then this is where your search ends!

- The original paper on this can be found [here](https://arxiv.org/abs/1803.04831)

- IndRNN implementation in keras is taken from [here](https://github.com/titu1994/Keras-IndRNN)

