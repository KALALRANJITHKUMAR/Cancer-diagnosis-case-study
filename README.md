# Cancer-diagnosis-case-study
### Problem statement :
Classify the given genetic variations/mutations based on evidence from text-based clinical literature.
#### Real-world/Business objectives and constraints.
* No low-latency requirement.
* Interpretability is important.
* Errors can be very costly.
* Probability of a data-point belonging to each class is needed.
#### Our constraints
* Interpretability
* Class probabilities are needed.
* Penalize the errors in class probabilites => Metric is Log-loss.
* No Latency constraints
