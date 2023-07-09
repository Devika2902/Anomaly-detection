# Anomaly-detection
This study aims to develop a noise-based predictive maintenance approach for devices using device noises. The MIMII pump dataset is utilized in this study, which contains acoustic and vibration signals of pumps under normal and anomalous conditions.

Based on the experiments conducted, we have found that
SVM with a linear kernel performed the best in detecting
anomalies in the MIMII pump dataset. The model achieved
an accuracy of 94%, outperforming SVM with default
parameters, Random Forest, and KNN.
When comparing the confusion matrices, we observed that
the SVM with linear kernel model had the fewest false
positives and false negatives, indicating that it was better at
identifying anomalous behavior in the pump recordings.
The precision, recall, and F1 score were consistently higher
for SVM with linear kernel compared to the other models,
further confirming its superiority in detecting anomalies.
