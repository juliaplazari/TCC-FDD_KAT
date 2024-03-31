# Bearing Fault Detection through Vibration and Current Signals decomposed with EMD and SSA

Repository for the codes used in the final thesis of my graduation, in which I used the [KAT dataset](https://mb.uni-paderborn.de/kat/forschung/kat-datacenter/bearing-datacenter) for fault detection

The goal of the project was to test different methods of decomposing the time series and different classifiers:

- Time series decomposition: [Empirical Mode Decomposition](https://emd.readthedocs.io/en/stable/index.html) and [Singular Spectrum Analysis](https://pyts.readthedocs.io/en/stable/auto_examples/decomposition/plot_ssa.html)

- Classification algortihms: [SVM](https://scikit-learn.org/stable/modules/generated/sklearn.svm.SVC.html), [Random Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html) and  a simple [Neural Network](https://www.tensorflow.org/tutorials/quickstart/beginner)

The folder in this repository have all the codes used, divided by time series decomposition in which I saved the datasets to be used in the classification and then one folder for each classifier.
