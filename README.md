# Improving Robustness: When and How to Minimize or Maximize the Loss Variance [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/valeriu-balaban/improving-robustness-with-variance-penalization/blob/main/improving_robustness_with_variance_penalization.ipynb)


This repository contains the source code and extended proofs supporting the paper. 
The easiest way to get started using this code is by running [this Colab notebook](https://colab.research.google.com/github/valeriu-balaban/improving-robustness-with-variance-penalization/blob/main/improving_robustness_with_variance_penalization.ipynb). The notebook requires having a [Weights & Biases](https://wandb.ai/) account to save the experimental results.

## Distributional Variance Penalization (FindQ)

Current Python implementation of the [FindQ procedure](https://github.com/valeriu-balaban/improving-robustness-with-variance-penalization/blob/07e0f3b8b530c3bada698a9da6e4defea7890507/robust_losses.py#L889) extends the one of [Daniel Levy](https://github.com/daniellevy/fast-dro) so it can also be used for variance maximization.


