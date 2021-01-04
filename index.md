---
layout: page
title: Winter 2021
---

This course surveys how networks of neurons can perform computation. We will cover a variety of methods for designing and training neural networks. We will study some state-of-the-art methods for artificial neural networks, as well as some approaches that are guided by the biological constraints of the brain. We will look at both supervised and unsupervised learning, and methods to improve their performance.

## Instructor
[Jeff Orchard](http://cs.uwaterloo.ca/~jorchard)

## Suggested Prerequisites
- one of ([CS 370](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS370), [CS 371](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS371)/[AMATH 242](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-AMATH.html#AMATH242)), [STAT 230](https://ucalendar.uwaterloo.ca/2021/COURSE/course-STAT.html#STAT230)

## Goals
By the end of the course, students will be able to:
- Write a program to simulation the activity of a network of neurons
- Formulate a neural learning method as gradient-based optimization
- Derive a neural learning method based on energy minimization
- Encode and decode data from the activity of a population of neurons
- Evaluate implementations, designs, and optimization strategies
- Identify some commonalities between artificial neural networks and the brain

## Textbooks
- *Theoretical Neuroscience*, Dayan and Abbott, 2001 ([UW library link](http://books.scholarsportal.info.proxy.lib.uwaterloo.ca/viewdoc.html?id=/ebooks/ebooks2/pda/2011-12-01/1/11936.9780262041997))
- *Neural Networks and Deep Learning*, Nielsen, 2017 ([link](http://neuralnetworksanddeeplearning.com/index.html))
- *Deep Learning*, Goodfellow, Bengio and Courville, 2016 ([link](http://www.deeplearningbook.org/))
- *Neural Engineering*, Eliasmith and Anderson, 2003: MIT Press.

## Lecture Schedule
The course will be offered online. There will be pre-recorded lecture videos, as well as some live tutorials each week (recorded).
- Tutorial time: TBD

## Evaluation
The course will have several assignments, a midterm, and final exam. Assignments will involve programming in Python. The approximate grade breakdown is:
- 20% Quizes
- 40% Assignments
- 10% Peer Evaluation
- 30% Final Assessment
  - Take-home final exam for those taking CS 489, or
  - Project for those taking CS 698

## Topics

1. Background
- Neuron models, spiking vs. firing-rate
- Activation functions
- Synapses
- Networks of neurons
- Learning: supervised/unsupervised/reinforcement

2. Supervised Learning
- Train, validation, testing
- Universal approximation theorem
- Cost functions
- Gradient descent
- Error backpropagation
- Automatic differentiation
- Overfitting and generalizability (regularization)
- Optimization considerations (vanishing gradients, SGD)
- Convolutiononal neural networks

3. Unsupervised learning
- Autoencoders
- Hopfield networks, Hopfield energy

4. Recurrent Neural Networks
- Backprop through time (BPTT)
- Long short-term memories (LSTM)

5. Advanced Topics (time permitting)
- Adversarial attacks
- Variational autoencoders
- Vector embeddings

6. Additional Topics (as time permits)
- Biological backprop models
- Population coding


