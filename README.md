# HM-Detect
HM-Detect is a novel heart murmur detection and classification method using techniques in sound feature analysis, signal processing, and machine learning.

This method was trained on the CirCor DigiScope Phonocardiogram Database. As of right now, v9 seems to be the most successful based on ROC curves. The CirCor Database is available online but is not included in this repository.

Several LSTM layers are used to classify the timing of a heart murmur between fundamental sounds S1 and S2 (early-, mid-, late-, or holo-systolic).

