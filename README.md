# DAVIAN Lab. Deep Learning Winter Study (2021)

- **Writer:** Sunjun Kweon

## Information

- **Title:** (cs231n) Lecture 4 : Introduction to Neural Networks 
- **Link:** http://cs231n.stanford.edu/slides/2020/lecture_4.pdf
- **Keywords:** Neural Networks, Backpropagation
-------------------------------------------------------

## Neural Network

- Motivation : Linear classifers are not very powerful

- Challenges : Viewpioint variation, Background clutter, Illmination, Deformation, Occlusion, Intraclass variation, .....
- Many attempts have been made...

### Machine Learning : Data-Driven Approach

1. Collect a datasest of images and labels
2. Use Machine Learning to train a classifier
3. Evaluate the classifier on new images

## Nearest Neighbor : the simplest classifier
1. Memorize all data and labels
2. Predict the label of the most similar training image
  - For each test image, find **closest train image** and predict label of nearest image
