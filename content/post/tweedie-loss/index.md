---
title: Tweedie Loss Function
subtitle: Describing the Tweedie distribution for predictive models

# Summary for listings and search engines
summary: In this post on medium, I describe the Tweedie loss function and how it can be used to model zero-inflated data.

# Link this post with a project
projects: []

# Date published
date: "2021-01-23T00:00:00Z"

# Date updated
lastmod: "2021-01-23T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Example of a zero-inflated distribution'
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- Machine Learning
- Data Science
- Regression
- Loss Function


categories:
- Medium Post

---

## Overview

In this [**Medium post**](https://sathesant.medium.com/tweedie-loss-function-395d96883f0b) I discuss the Tweedie distribution and use of the tweedie loss function and how to implement this in Python. When building predictive models, it is not uncommon to observe data with right-skewed distribution and long tail. For example, in a large e-commerce company like Amazon, most users entering the site will likely not make a purchase, and if they do, the value ranges between cents and thousands of dollars. As a consequence we may have oddly shaped "zero-inflated" distributions with a point mass at zero. Under this circumstance, prediction models may not be well trained if loss functions for other distributions (e.g., RMSE for Gaussian distributions) are used.
