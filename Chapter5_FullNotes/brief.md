## Section 5.1 - Neural Network Basics
This is one of the main components and one that is most popular. It related to DL and ML too. <br>

**Neural Network**: can mean either a real biological neural network (our brain) or an artificial neural network like one simulated in a computer.

**Key Terminology Below**:
- Deep learning is a subset of ML. So it refers to kinds of ML techniques where a lot of layers of processing units are connected in a network so that the input to the system is passed through each one of them in turn. This allows for more complex structures without requiring such large amounts of data.
- A neural network consists of a large number of simple neurons which receive and transmit signals to each other. They are simple processors of information that has a body and wires that connect. Usually, they do nothing until information comes in.

<br>

**Neural Network Importance + Features**:
- We do this because by simulating low level data processing on the neurons and networks, we can get intelligence.
- Feature1: The system consists of a large number of neurons each of which can process information on its own so that insteaf of having a CPU process each piece of information, the neurons do it together.
- Feature2: Neurons store and process information so that there is no need to retreive data from the memory for processing. The data can be stored short term in the neurons themselves or longer via the connections between them.

---

## Section 5.2 - How Neural Networks are Built
- The basic artificial neuron model involves a set of adaptive parameters, called weights. Just like in regression, these weights are used as multipliers on the inputs of the neuron, which are added up. The sum of the weights times the inputs is called the linear combination of the inputs.
- Neurons activate by using activation functions that output a continuous numerical activation level at all times, such as the sigmoid function. Thus, artificial neurons communicate by adjusting the pitch of their voice as if yodeling.
- The output of the neuron, determined by the linear combination and the activation function, can be used to extract a prediction or a decision. For example, if the network is designed to identify a stop sign in front of a self-driving car, the input can be the pixels of an image captured by a camera attached in front of the car, and the output can be used to activate a stopping procedure that stops the car before the sign.

<br>

**Key Terminology**:
- Often the network architecture is composed of layers. The input layer consists of neurons that get their inputs directly from the data. So for example, in an image recognition task, the input layer would use the pixel values of the input image. The network typically also has hidden layers that use the other neurons’ outputs as their input, and whose output is used as the input to other layers of neurons. Finally, the output layer produces the output of the whole network. All the neurons on a given layer get inputs from neurons on the previous layer and feed their output to the next.

---

## Section 5.3 - Advanced Neural Network Techniques
This will all be covered in a different repo along with its project
- CNNs (Convolutional Neural Networks)
- GANs (Generative Adversarial Networks)
- LLMs (Large Language Models)
