# HM-Detect
HM-Detect is a novel heart murmur detection and classification method using techniques in sound feature analysis, signal processing, and machine learning.

In this project, several LSTM layers are used to classify the timing of a heart murmur between fundamental sounds S1 and S2 (early-, mid-, late-, or holo-systolic). This method was trained on the CirCor DigiScope Phonocardiogram Database and the Michigan Heart Sound & Murmur Library.

The CirCor Database and Michigan Heart Sound & Murmur Library are available online but are not included in this repository. Extra folders were made to store spectrograms, GAN plots, SSEs, TensorFlowJS models, Time Series Data and Time Series Data Five Seconds plots, and of course the two training databases mentioned before.

As of right now, v9 seems to be the most successful based on ROC curves.
