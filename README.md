# how-to-dp-fy-ml
How to DP-fy ML tutorial

This repository contains colabs complementing our tutorial for ICML and KDD 2023: "How to DP-fy ML".

1. A base example on how to implement DP-SGD in Tensorflow Privacy can be found https://github.com/tensorflow/privacy/blob/master/g3doc/tutorials/classification_privacy.ipynb
2. Building on it, "Label_DP_Example_on_MNIST.ipynb" demonstrates how to go from full training data protection, to label-only protection (assuming the features are public).
3. "Calculating post-hoc privacy guarantees for DP-SGD.ipynb" shows how to calculate guarantees for DP-SGD or other DP-Training (gradient noise injection based methods) runs post-factum.
4. For user-level privacy preserving algorithm DP-FedAvg check out this colab https://www.tensorflow.org/federated/tutorials/federated_learning_with_differential_privacy
5. For additional colab demonstrating how to calculate privacy cost for hyperparameter tuning using various methods, refer to https://gist.github.com/carsondenison/d69e0b86f98af6d4f2d086d26859f6ec
   


Additional material
* Our survey paper (accepted to JAIR 2023) https://arxiv.org/abs/2303.00654 that surved as a source for the tutorial
* Promotional video for KDD https://github.com/tensorflow/privacy/blob/master/g3doc/tutorials/classification_privacy.ipynb
* ICML tutorial link https://icml.cc/virtual/2023/tutorial/21560
* KDD tutorial link https://kdd.org/kdd2023/tutorials/ LS-14
* Blog post https://ai.googleblog.com/2023/05/making-ml-models-differentially-private.html






