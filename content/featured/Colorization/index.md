---
date: '5'
title: 'Colorization'
cover: './colorization.png'
github: 'https://github.com/NeilJain56/Colorization'
external: '#'
tech:
  - Python
  - Neural Networks
showInProjects: false
---

This project builds a neural network from scratch and aims to take a gray-scale image and colorize it. In order to train the network the program first takes the image as input and preprocesses the data the determine the input vector. It then forward propagates through a pre-decided number of hidden layers and nodes. These nodes use the sigmoid activation function to determine the output vector from the given layer. Once the final answer is given, we then compute the loss and use gradient descent to update the weight values. 
