## Task II: Quantum Generative Adversarial Network (QGAN) Part

You will explore how best to apply a quantum generative adversarial network (QGAN) to solve a High Energy Data analysis issue, more specifically, separating the signal events from the background events. You should use the Google Cirq and Tensorflow Quantum (TFQ) libraries for this task.


A set of input samples (simulated with Delphes) is provided in NumPy NPZ format
[​ Download Input​ ]. In the input file, there are only 100 samples for training and 100
samples for testing so it won’t take much computing resources to accomplish this
task. The signal events are labeled with 1 while the background events are labeled
with 0.


Be sure to show that you understand how to fine tune your machine learning model
to improve the performance. The performance can be evaluated with classification
accuracy or Area Under ROC Curve (AUC).