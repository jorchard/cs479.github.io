---
layout: page
title: CS 479/679: Neural Networks
---

This web page is a summary of the course. For the official details, please refer to its [listing in the Undergraduate Calendar](https://uwaterloo.ca/academic-calendar/undergraduate-studies/catalog#/courses/B1of5VXY2?bc=true&bcCurrent=CS479%20-%20Neural%20Networks&bcGroup=Computer%20Science%20(CS)&bcItemType=courses).

This course surveys how networks of neurons can perform computation. We will cover a variety of methods for designing and training neural networks. We will study some state-of-the-art methods for artificial neural networks, as well as some approaches that are guided by the biological constraints of the brain. We will look at both supervised and unsupervised learning, and methods to improve their performance.

## Instructor
[Jeff Orchard](http://cs.uwaterloo.ca/~jorchard), and [Mohamed Hibat-Allah](https://uwaterloo.ca/applied-mathematics/profiles/mohamed-hibat-allah)

## Prerequisites
- one of ([CS 370](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS370), [CS 371](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-CS.html#CS371)/[AMATH 242](http://www.ucalendar.uwaterloo.ca/1920/COURSE/course-AMATH.html#AMATH242))
- one of ([STAT 206](https://ucalendar.uwaterloo.ca/2021/COURSE/course-STAT.html#STAT206) with a grade of at least 60%, [STAT 230](https://ucalendar.uwaterloo.ca/2021/COURSE/course-STAT.html#STAT230), [STAT 240](https://ucalendar.uwaterloo.ca/2021/COURSE/course-STAT.html#STAT240))

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

## Evaluation (tentative)
The course will have several assignments, a midterm, and final Assessment. Assignments will involve programming in Python.

For **CS 479**, the grade breakdown is:
- 30% Assignments
- 20% Midterm Exam
- 50% Final Exam

For **CS 679**, the grade breakdown is:
- 50% Assignments
- 20% Midterm Exam
- 30% Final Project


## Topics

**Neuron Models**
- Neuron models, spiking vs. firing-rate
- Activation functions
- Synapses
- Networks of neurons

**Supervised Learning**
- Train, validation, testing
- Universal approximation theorem
- Cost functions
- Gradient descent
- Error backpropagation
- Automatic differentiation
- Overfitting and generalizability (regularization)
- Optimization considerations (vanishing gradients, SGD)

**Vision**
- Your Visual System
- Convolutiononal neural networks

**Recurrent Neural Networks**
- Hopfield Networks
- Backprop through time (BPTT)
- minGRU

**Unsupervised Learning**
- Autoencoders
- Vector embeddings

**Advanced Autoencoders**
- Restricted Boltzmann Machines (RBMs)
- Residual connections, Diffusion networks
- Variational autoencoders (VAEs)

**Adversarial Attacks**
- Targeted vs untargeted
- FGSM
- Defences: TRADES

**Neural Engineering**
- Optimal linear decoding
- Transformations, dynamics

**Advanced Topics** (time permitting)
- Biological backprop models
- GANs
