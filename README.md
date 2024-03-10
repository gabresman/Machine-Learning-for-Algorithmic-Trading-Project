# Machine-Learning-for-Algorithmic-Trading-Project

This study focuses on developing a machine learning-based trading algorithm for the NASDAQ Composite index, aiming to outperform both in profitability and risk its benchmark index. To achieve this, an architecture is implemented to extract data from various sources and utilizes a persistent SQL storage solution. The dynamics governing financial markets are explored through an exploratory data analysis, followed by the application of various preprocessing techniques to financial time series data.

During the model training and evaluation phase, the predictive capability of algorithms such as Extreme Gradient Boosting (XGBoost), Support Vector Machine, Random Forest, and recurrent neural networks like Long Short-Term Memory is tested for this type of problem. The best of these algorithms is combined with the K-Nearest Neighbors (KNN) algorithm in an innovative technique based on the union of supervised and unsupervised classification.

Once predictions are made, ensembles between different algorithms are explored to improve predictive capability and reduce risk. Finally, a model is constructed by assembling the K-Nearest Neighbors, Extreme Gradient Boosting, and Random Forest algorithms, generating a return of 155.60% between 2021 and 2023, during a period when the NASDAQ Composite fell by -6.41%.

These results are obtained through preprocessing techniques such as Wavelet Transform, Normalization, and Stacked Autoencoders, whose contribution to predictive capability is compared and discussed across different algorithms.
