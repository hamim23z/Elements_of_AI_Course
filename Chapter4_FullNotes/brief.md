## Section 4.1 - Types of Machine Learning
Handwritten digits are a classic case that is often mentioned when talking about ML. Everyone has different handwriting and it can be hard to understand what something really is, like is that really a 5 or is it an S?
<br>

MNIST: Modified National Institute of Standards and Technology. It is a dataset essentially.
<br>
<br>

**Three Types of Machine Learning**
- So ML roots are in statistics. We extract knowledge from data and use that data to improve performance. <br>
1. **Supervised Learning**: we are given an input (photo with sign) and predict the correct output (what kind of traffic sign is it?). In the simplest case, the answer is in the form yes or no because we give it different signs and essentially ask, is it this traffic sign or not?
2. **Unsupervised Learning**: There are no labels or correct outputs. We discover the structure of the data by grouping and then find patterns. Data visualization is a prime example of this.
3. **Reinforcement Learning**: Used in situations where an AI agent (self driving car) must operate and where feedback about good/bad choices is available with some delay. Also used in games where outcome decided at end only. (Review this one more)

<br>

**Classification**: When dealing with ML, its usually supervised learning. We observe in input and try to infer what kind of type it is. We identify something and then decide something.
<br>
<br>

--- 

### Supervised Learning
The point in supervised learning is to take a number of examples, label each one correctly, and then use them to train an AI Model to automatically recognize the correct label for the training examples as well as any new example that we may use. Hence the name supervised, we are essentially telling our AI what to look for, what to recognize, and what to do correctly. 

<br>

**What NOT to do**
- When first dabbling with ML, we may be confident with the accurary of our predictions. But buddy thats wrong. We need to first split the data into two parts. The training data and the test data. We first train our ML using only the training data. This gives us a rule that predicts output based on the input variable. And to actually assess how well we can predict the outputs, we then use the test data and compare.

--- 

### Unsupervised Learning
The main difference here is that we do not have correct answers. So we cannot make the model by making it fir the correct answers on training data. This does seem a lot harder but it is possible. What we do is just data visualization and clustering where we use the data to identify groups or items that are similar to each other. 

```
Things to Read up on
- Generative modeling
- Generative Adversarial Networks (GANs)
```
