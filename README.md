# Analyzing Aftershock Patterns in Bogo City, Cebu using Unsupervised and Supervised Learning
Overleaf Link: https://www.overleaf.com/3137729714tjsyjrhpdmkf#7a10d5
Authors: Charrie Anne Nacor and Joanna Marie Pagtalunan

The Bogo Bay Fault, a previously undermapped fault just offshore northern Cebu, ruptured during a 6.9 magnitude earthquake on September 30, 2025, near Bogo City. Since the earthquake, the region has continued to experience a sequence of aftershocks. 

This notebook implements a two-step approach to analyze this aftershock sequence.

1. **Unsupervised Learning.** Identify natural groupings in the aftershock data based on location, depth, magnitude, and timing
2. **Supervised Learning.** Train classifiers to evaluate whether the identified clusters identified by the unsupervised algorithm are meaningful and well-separated

We will compare

* **Clustering Methods.** K-Means vs K-Medoids
* **Classification Methods.** Support Vector Classifier (SVC) vs XGBoost
