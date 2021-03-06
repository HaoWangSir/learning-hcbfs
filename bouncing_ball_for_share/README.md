# Learning HCBFs from Data - Bouncing Ball Case Study

Code for the bouncing ball case study in "Learning Hybrid Control Barrier Functions from Data".

## Getting Started

1. Simply run the code blocks in the [notebook](https://github.com/unstable-zeros/learning-hcbfs/blob/main/bouncing_ball_for_share/bouncing_ball_for_share.ipynb) top-down to reproduce our results
2. Load the training data: [X_train_cts.npy](https://github.com/unstable-zeros/learning-hcbfs/blob/main/bouncing_ball_for_share/data/X_train_cts.npy), [U_train_cts.npy](https://github.com/unstable-zeros/learning-hcbfs/blob/main/bouncing_ball_for_share/data/U_train_cts.npy) in the [data](https://github.com/unstable-zeros/learning-hcbfs/tree/main/bouncing_ball_for_share/data) folder (optional)
3. Load the learned HCBF: [params.npy](https://github.com/unstable-zeros/learning-hcbfs/tree/main/bouncing_ball_for_share/network) in the [network](https://github.com/unstable-zeros/learning-hcbfs/tree/main/bouncing_ball_for_share/network) folder (optional)


### Prerequisites

[Google Colab](https://colab.research.google.com/) recommended for running the code.

## Acknowledgments

* The hybrid integrator is developed based on [Drake](https://drake.mit.edu/)
