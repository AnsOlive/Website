---
title: "My First Logistic Regression Model"
date: 2025-02-05
description: "My first experience applying the logistic regression deep learning method."
tags: []
categories: ["Research", "Code", "Deep Learning"]
draft: false
---

# Thanks for dropping in!

This project taught me even more about deep learning basics. Using a logistic model is interesting because it allows the model to have a general rule for making descisions based on past descision data. I am currently unsure of how this function could be change to gather real-time descision data but that is something I want to look into more. I am also curious about feedback on the model's descisions from choices it has made- I assume for the example where it is chip manufacturing the priority should be weighted so the sucesses scrapped are prefered over failures that are shipped.

## What did I learn from this project?

I liked logistic regression in particular due to the problem containing a use case, making it easier to understand how/why this model is used. This introduced several new factors such as regularization and using the hypothesis in the gradient descent/loss.

## Basis

This was my first experience with logistic regression and also was assigned by a professor as homework but I still thought it was interesting and useful enough to post about what I learned.

## Photographic Results

I have embedded four photos below that unfortunately do not seem to work all that well at the moment since I still need to take some time to see why it will not embed on this site properly.

### 3D Data Visulaization of the Data

This is a 3D plot of the tree dataset provided- this essentially creates a graph depicting the volume on the z-axis and the girth on the x-axis and height on the y-axis. This is the training data of this model- the data used to predict the optimized parameters.
While I work on embedding the photo please visit: http://ansonprojects.com/static/images/No_Reg.png
While I work on embedding the photo please visit: http://ansonprojects.com/static/images/Reg.png

### The Losses as Iterations Increase for Different Learning Rates

This are screenshots of the losses as iterations increase when using differnet learning rates for this linear regression model.
While I work on embedding the photo please visit: http://ansonprojects.com/static/images/No_Reg_Iter.png
While I work on embedding the photo please visit: http://ansonprojects.com/static/images/Reg_Iter.png

## Code

You can find the code used for these results at [https://github.com/AnsOlive/Deep_Learning under the name nuen_489_homework_1.py](https://github.com/AnsOlive/Deep_Learning/blob/main/nuen_489_homework_1.py)