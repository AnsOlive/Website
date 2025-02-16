---
title: "My First Logistic Regression Model"
date: 2025-02-05
description: "My first experience applying the logistic regression deep learning method."
tags: []
categories: ["Research", "Code", "Deep Learning"]
draft: false
---

# Thanks for dropping in!

This project taught me even more about deep learning basics. Using a logistic model is interesting because it allows the model to have a general rule for making decisions based on past decision data. I am currently unsure of how this function could be changed to gather real-time decision data, but that is something I want to look into more. I am also curious about feedback on the model's decisions from choices it has made—I assume for the example where it is chip manufacturing, the priority should be weighted so that the successes scrapped are preferred over failures that are shipped.

## What did I learn from this project?

I liked logistic regression in particular due to the problem containing a use case, making it easier to understand how/why this model is used. This introduced several new factors, such as regularization and using the hypothesis in the gradient descent/loss.

## Basis

This was my first experience with logistic regression. It was assigned as homework by a professor, but I still thought it was interesting and useful enough to post about what I learned.

## Photographic Results

I have embedded four photos below that now properly reference the images from the `static/images` directory.

### Regularization Comparison

These are plots of the data both before and after regularization, respectively. You can see that the decision boundaries are similar but not exactly the same before and after regularization.

![No Regularization](static/images/No_Reg.png)

![With Regularization](static/images/Reg.png)

### Loss Comparison

These are screenshots of the losses as iterations increase when using no regularization versus a regularization of one. As you can see, the loss converges much more quickly when regularized but converges to a higher loss than the non-regularized solution.

![Loss Without Regularization](static/images/No_Reg_Iter.png)

![Loss With Regularization](static/images/Reg_Iter.png)

## Code

You can find the code used for these results at [https://github.com/AnsOlive/Deep_Learning](https://github.com/AnsOlive/Deep_Learning/blob/main/nuen_489_homework_1.py)