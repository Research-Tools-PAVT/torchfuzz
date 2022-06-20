# TorchFuzz: Coverage Guided Fuzzing for Neural Networks (TensorFuzz -- PyTorch)

This repository contains a library for performing coverage guided fuzzing of neural networks,
as was described in [this paper](https://arxiv.org/abs/1807.10875).

Migration of Tensorfuzz to work with PyTorch so it's torchfuzz.
Coverage guided fuzzing for PyTorch models.

## Installation

You ought to be able to run the code in this repository by doing the following:

```
pip install -r requirements.txt
```

Then do:

```
export PYTHONPATH="$PYTHONPATH:$HOME/tensorfuzz"
```