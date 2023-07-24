# Andrew-s-Plot-for-Different-Ragas
Background:
Andrews curves, also known as Andrews plot, are a visualization technique used to identify underlying structure in multidimensional data. Similar to principal component analysis and T-distributed stochastic neighbor embedding, Andrews curves reduce multiple features into low dimensional space to display relationships with target variables or classifications. Andrews curves work by mapping all features from a single observation or row of data onto a function. This function is defined as:
T(n) = x_1/sqrt(2) + x_2 sin(n) + x_3 cos(n) + x_4 sin(2n) + x_5 cos(2n) + …
https://upload.wikimedia.org/wikipedia/commons/0/03/Andrews_curve_for_Iris_data_set.png

The resulting function output creates a unique curve, maintaining relative distance and variance across all features per function coefficient and between observations. Another way to think of Andrews curves may be a transformed version of a parallel coordinates plot. Combined with multiple observations and distinguished by target variable color mappings, Andrews curves highlight potential clusters among classes or separation between them.
