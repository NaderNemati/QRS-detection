# QRS-detection

The input in this python program is ECG signals, which has processed by filtering and thresholding.
In the beginning, during the filtering, each signal was filtered using low-pass and high-pass filters together by using a band-pass filter. This filtering method ensures that only parts of signals related to heart activity can pass. The band-pass filtered signal is then differentiated to identify signal segments with high signal change values. Next, The program detects QRSs by considering the thresholds. A threshold in a given moment is based on the signal value of the previously detected QRS and noise peaks.
