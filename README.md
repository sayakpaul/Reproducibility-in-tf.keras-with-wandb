Accompanies with [this report](https://app.wandb.ai/sayakpaul/reproducible-ml/reports/Reducing-the-reproducibility-burden-in-ML-with-W%26B--Vmlldzo3ODMxNQ).

There are different levels of stochasticity in machine learning (ML). Sometimes it's there in the sampling process of the dataset, sometimes in the machine learning models (specifically neural networks) themselves. While stochasticity brings a number of advantages in a machine learning model, it causes some genuine problems with regards to reproducibility. 

The repository includes some code as showcased in the above-mentioned report. 

## Overview of the methods covered

- Uniform hardware and software setup
- Random seeds + fixed (initial) weights
- Data-related nuances
- Hyperparameter sorcery
- Version control for keeping sanity
- Writing correctness tests
- Model checkpointing and beyond

## Coded in
- TensorFlow 2.1
- Weights and Biases 

## Machine used:
- `n1-standard-4vCPUs-15GB`
- Tesla V100
- Preconfigured Image: TensorFlow 2.1 (with Intel MKL-DNN/MKL and CUDA 10.1)
