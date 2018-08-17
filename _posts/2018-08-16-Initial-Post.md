---
layout: post
title: "Raylyn's Blog Post 1"
date: 2018-08-16
week: Week 1
---

vised learning. Imagine that we want to build a system that can classify 
images as containing, say, a house, a car, a person or a pet. We first 
collect a large data set of images of houses, cars, people and pets, each 
labelled with its category. During training, the machine is shown an 
image and produces an output in the form of a vector of scores, one 
for each category. We want the desired category to have the highest 
score of all categories, but this is unlikely to happen before training. 

tance) between the output scores and the desired pattern of scores. The 
machine then modifies its internal adjustable parameters to reduce 
this error. These adjustable parameters, often called weights, are real 

tion of the machine. In a typical deep-learning system, there may be 
hundreds of millions of these adjustable weights, and hundreds of 
millions of labelled examples with which to train the machine. 

putes a gradient vector that, for each weight, indicates by what amount 
the error would increase or decrease if the weight were increased by a 

tion to the gradient vector. 
The objective function, averaged over all the training examples, can 
