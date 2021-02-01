# DAVIAN Lab. Deep Learning Winter Study (2021)

- **Writer:** Sunjun Kweon

## Information

- **Title:** (cs231n) Lecture 4 : Introduction to Neural Networks 
- **Link:** http://cs231n.stanford.edu/slides/2020/lecture_4.pdf
- **Keywords:** Neural Networks, Backpropagation
-------------------------------------------------------

## Neural Network

- Motivation : Linear classifers are not very powerful
![1](https://user-images.githubusercontent.com/59158426/106470232-98de6e80-64e3-11eb-85c2-0257ecc74dde.PNG)

- Stacking multiple layers with non-linearity expresses more

![2](https://user-images.githubusercontent.com/59158426/106471208-bf50d980-64e4-11eb-8093-1c9ecde09bbe.PNG)
- Instead of just having linear score **s=W1x** 2-layer neural network's score is **s=W2f(W1x)**

### Machine Learning : Data-Driven Approach

1. Collect a datasest of images and labels
2. Use Machine Learning to train a classifier
3. Evaluate the classifier on new images

## Nearest Neighbor : the simplest classifier
1. Memorize all data and labels
2. Predict the label of the most similar training image
  - For each test image, find **closest train image** and predict label of nearest image
