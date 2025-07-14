---
name: Use of Neural Network Machine Learning Models in Calculating Peculiar Velocity and Galactic Distances
tools: [Python, TensorFlow, LaTeX]
#image:
description: BS Physics senior thesis, 2024
#external_url: https://github.com/yousinix
---

# Use of Neural Network Machine Learning Models in Calculating Peculiar Velocity and Galactic Distances

My senior thesis for my undergraduate degree applied an existing equation to new cosmological data using neural nets. 

### Project Concept 

The calculation of galactic distances is a critical part of cosmological research. There are a number of existing methods, but the one of particular interest to this project was the baryonic Tully-Fisher Relation (bTFR), which is used for calculating the distances to spiral galaxies. 

This project used the equation that makes up bTFR and generalized it by making the variables inputs into a neural network. It trained and tested that neural net on real and simulated Cosmicflows-4 (CF4) data. The goal was to use this vast amount of CF4 data to produce an algorithm that can provide high-accuracy distance values when given information about a galaxy. 

### Skills Used 

- Python
    - TensorFlow
    - Matplotlib.pyplot
- LaTeX

### Project Result

A number of models were produced using the simulated CF4 data as a proof of concept. These were then applied to real CF4 data, in a novel method that did not require reliable target values for prediction. Overall, this project showed that neural nets could be used to calculate galactic distances. 

<p class="text-center">
{% include elements/button.html link="../Kaiden-Elam_Final-Thesis.pdf" text="Read the Paper" %}
</p>