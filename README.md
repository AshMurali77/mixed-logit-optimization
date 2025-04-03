# Mixed Logit Optimization Modeling
This project implements a Mixed Logit Model in PyTorch to predict consumer choice behavior among competing vehicle types based on price, cost, fuel type, distance, and performance. As part of an Optimization Methods course, the project explores the impact of various hyperparameters (learning rate, momentum), customer segment counts, and batch sizes on model performance.

It compares vanilla SGD and momentum-based optimizers, and measures in-sample vs out-of-sample loss to assess generalization. Batch size sensitivity and testing accuracy are also analyzed to determine optimal training configurations.

Note: The raw dataset is provided separately and not included in this repository. While the model was developed in Google Colab, it is compatible with local execution.
Optimization-driven implementation of a Mixed Logit Model in PyTorch to predict vehicle choice behavior. Explores effects of optimizer tuning, customer segmentation, and batch size on generalization.
