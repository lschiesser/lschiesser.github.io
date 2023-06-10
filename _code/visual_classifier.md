---
title: "Visual Classifier"
collection: code
permalink: /code/visual_classifier
excerpt: "A python script to visually classify a set of images in user defined categories."
date: 2018-05-15
repo: "https://github.com/matthewkirby/VisualGalaxyClassification"
---
## Summary
I wrote a python script that can be used to visually classify images. The code displays the images in [DS9](http://ds9.si.edu/site/Home.html) but it is fairly simple to change this to whatever display software you like. It allows for the user to supply their own list of classification and flag options and outputs results to a plain text file. The goal of this package is that a user can pick it up and rapidly classify a large sample of images. 

In additional to classifying a final sample, the code also has a training option where a classifier is shown images with known classifications that the user supplies. After completing the sample, the code "grades" the classifier based on their accuracy.

## Dependencies
* DS9
* Python 2 and 3 compatible
* Python packages
   * PyDS9
   * easygui
