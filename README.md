# Elements_of_AI_Course

The link to this course can be found at https://www.elementsofai.com/ . What I did was Part 1 "Introduction to AI". I did not fully do it as a lot of the information I will be getting from other courses. However, this was a great introductory course. Below are definitions to know for myself. 

---

## Definitions + Important Info
1. **Machine Learning**: systems that improve their performance in a given task with more data/experience.


2. **Deep Learning**: a type of machine learning based on artificial neural networks in which multiple layers of processing are used to extract progressively higher level features from data.
3. **Data Science**: include ML, stats, some CS. Its also a field to study and a career path.
4. Computer Science -> Artificial Intelligence -> Machine Learning -> Deep Learning
5. **General (Artificial General Intelligence) vs Narrow AI**  So Narrow AI is the one that we all use to this day, it completes one task. AGI is something that is fiction, it will complete more than one task and essentially everything. 
6. Supervised Learning: we are given an input (photo with sign) and predict the correct output (what kind of traffic sign is it?). In the simplest case, the answer is in the form yes or no because we give it different signs and essentially ask, is it this traffic sign or not?
7. **Unsupervised Learning**: There are no labels or correct outputs. We discover the structure of the data by grouping and then find patterns. Data visualization is a prime example of this.
8. **Reinforcement Learning**: Used in situations where an AI agent (self driving car) must operate and where feedback about good/bad choices is available with some delay. Also used in games where outcome decided at end only. (Review this one more)

9. **Classification**: When dealing with ML, its usually supervised learning. We observe in input and try to infer what kind of type it is. We identify something and then decide something.

10. **Supervised Learning**: The point in supervised learning is to take a number of examples, label each one correctly, and then use them to train an AI Model to automatically recognize the correct label for the training examples as well as any new example that we may use. Hence the name supervised, we are essentially telling our AI what to look for, what to recognize, and what to do correctly.

11. **Unsupervised Learning**: The main difference here is that we do not have correct answers. So we cannot make the model by making it fir the correct answers on training data. This does seem a lot harder but it is possible. What we do is just data visualization and clustering where we use the data to identify groups or items that are similar to each other.

12. **Neural Network**: can mean either a real biological neural network (our brain) or an artificial neural network like one simulated in a computer.

13. Deep learning is a subset of ML. So it refers to kinds of ML techniques where a lot of layers of processing units are connected in a network so that the input to the system is passed through each one of them in turn. This allows for more complex structures without requiring such large amounts of data. A neural network consists of a large number of simple neurons which receive and transmit signals to each other. They are simple processors of information that has a body and wires that connect. Usually, they do nothing until information comes in.

14. **Neural Network Importance + Features**: Feature1: The system consists of a large number of neurons each of which can process information on its own so that insteaf of having a CPU process each piece of information, the neurons do it together. Feature2: Neurons store and process information so that there is no need to retreive data from the memory for processing. The data can be stored short term in the neurons themselves or longer via the connections between them.

15. The basic artificial neuron model involves a set of adaptive parameters, called weights. Just like in regression, these weights are used as multipliers on the inputs of the neuron, which are added up. The sum of the weights times the inputs is called the linear combination of the inputs.

16. Often the network architecture is composed of layers. The input layer consists of neurons that get their inputs directly from the data. So for example, in an image recognition task, the input layer would use the pixel values of the input image. The network typically also has hidden layers that use the other neurons’ outputs as their input, and whose output is used as the input to other layers of neurons. Finally, the output layer produces the output of the whole network. All the neurons on a given layer get inputs from neurons on the previous layer and feed their output to the next.
