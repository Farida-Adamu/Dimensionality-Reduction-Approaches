# Dimensionality-Reduction-Approaches
This repository contains code on the two primary methods used for dimensionality reduction in machine learning projects. 

Dimensionality reduction is the process of simplifying data by reducing the number of features (or dimensions) while retaining the most important information.

PCA finds new axes (called principal components) that capture the maximum variation in the data. It’s like finding the directions where the data spreads out the most.
RP reduces dimensions by projecting the data onto a randomly generated space.
When to Use:
	•	You have very high-dimensional data (like text or image data).
	•	You don’t need exact variance preservation, but want a quick approximation.
	•	Speed and scalability are priorities.

Files in this Repository

RandomProjection.ipynb: Shows how to apply random projection and analyze its effects on the data.
PCA.ipynb: Demonstrates how to use PCA for dimensionality reduction, with examples and visualizations.

In DR we try to answer on primary question. What parts of the data is important?
More variance = more information

PCA only works  on linearly related features
