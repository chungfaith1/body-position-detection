# body-position-detection

## Motivation

Individuals diagnosed with orthostatic hypotension (OH) experience an abrupt decrease in blood pressure after a change in body position from sitting to standing. This sudden pressure drop triggers lightheadedness, blurry vision, weakness, fainting, confusion, or even nausea. Current products for OH are compression stockings, abdominal binders, and intermittent pneumatic compression devices. Unfortunately, the passive solutions require significant amount of force to put on and off, especially for the elderly, and the powered devices require external air compressors, which requires the user to manually set their desired pressure level and limits the limits their mobility. 

For University of Maryland's Mechanical Engineering capstone project, my team sought to create a mobile and discrete product that autonomously increases pressure before or during the change in the user’s body position. The solution was an adominal binder with an autonomous corset-style tightening system, utilizing servos, pressure transducers, and a 3-axis accelerometer near the chest. As the user goes about their day, the accelerometer will detect when the user is standing up, prompting the motor assembly to start winding the corset cable. When a pressure of 30 mmHg has been reached, the motor will cease to increase pressure and hold the pressure for three minutes after orthostatic position was achieved. The pressure will be released after this time period has elapsed. 

## Problem

How do we utilize the 3-axis accelerometer data to determine whether or not someone is in the process of standing up?

*Note: I did not have a kinesiology background and did not have the bandwidth to derive a formula for this problem!*

## Solution

A 3 input neural network with 1 hidden layer, sigmoid activation functions, and gradient descent was used to return the probability that someone is standing up.

## Repo Contents

Data:

Data Visualization:

Neural Network: 
1. My own implementation without APIs
2. TensorFlow Implementation

## Lessons Learned

1.
2.
3.
