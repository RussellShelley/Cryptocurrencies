# Cryptocurrencies Analysis


## Overview


We will be using Unsupervised machine learning  in an investigation of cryptocurrencies for an investment bank. We will create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment oppurtunity.
In order to do this:

- We will first preprocess our data (using Pandas library to drop nulls, .get_dummies etc and standard_scaler)  for the PCA

- Reduce data dimensions using PCA(Principal Component Analysis).  The data will be reduced to three principal component. (PCA is a statistical technique that takes looks at variance and creates new target features.-CA can make ML models more efficient as the reduced feature set boosts learning rates, reduces computational costs and accuracy can improve. 

- Then we will cluster the cryptocurrencies using K-means, first creating an elbow chart to check for optimum K number.

- Finally, we will visualize these results. We will do this using 3-D scatter, hvp.plot table and 2D scatter plot.

## Resources
Jupyter notebook, pandas ,plotly, sklearn [crypto_data.csv]("./resources/crypto_data.csv")
