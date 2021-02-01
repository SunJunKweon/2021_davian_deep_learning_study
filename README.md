# DAVIAN Lab. Deep Learning Winter Study (2021)

- **Writer:** Sunjun Kweon

## Information

- **Title:** (cs231n) Lecture 4 : Introduction to Neural Networks 
- **Link:** http://cs231n.stanford.edu/slides/2020/lecture_4.pdf
- **Keywords:** Neural Networks, Backpropagation
-------------------------------------------------------

## Neural Network

- Motivation : Linear classifers are not very powerful. It is hard to classify things which cannot be divided by a single line(hyperplane)
![1](https://user-images.githubusercontent.com/59158426/106470232-98de6e80-64e3-11eb-85c2-0257ecc74dde.PNG)

- Stacking multiple layers with non-linearity expresses more

![2](https://user-images.githubusercontent.com/59158426/106471208-bf50d980-64e4-11eb-8093-1c9ecde09bbe.PNG)
- Instead of just having linear score **s=W1x** 2-layer neural network's score is **s=W2f(W1x)**
- f which contributes to non-linearity is called activation function. Below are popular choices for activation functions
![3](https://user-images.githubusercontent.com/59158426/106471511-0b038300-64e5-11eb-82e1-dd38e0bbd6ab.PNG)


## Backpropagtion

-Directly optimizing the whole neural network(getting the gradient) is complicated. Therefore we use backpropagation.

-Backpropgation comes from the chain rule

![4](https://user-images.githubusercontent.com/59158426/106472698-481c4500-64e6-11eb-9525-e67264e1fd88.PNG)

When we want to calculate the gradient(jacobian) of Loss with respect to a certain weight, we multiply the upstream gradient(which comes backward from the loss) with
the local gradient.
