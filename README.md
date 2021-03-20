# FCS
This repository includes codes and theoretical proofs for paper "Efficient Tensor Contraction via Fast Count Sketch". The TRN compression experiment is implemented in Python, while all other experiments are implemented in Matlab.

# Datasets
The datasets for realworld experiments can be downloaded here: https://drive.google.com/drive/folders/1RLAskW6_Cke7XP9bcaxRRTiaa9L5JmXR.
We use FMNIST for the TRN compression experiment, which is available at https://github.com/zalandoresearch/fashion-mnist.

# Requirements
Our code requires:
(1) Tensor Toolbox version 2.6 by Bader, Kolda and others (available at http://www.sandia.gov/~tgkolda/TensorToolbox/);

(2) Tensorlab version 3.0 by Vervliet N., Debals O., Sorber L., Van Barel M. and De Lathauwer L. (available at https://www.tensorlab.net/);

(3) Tensorflow 1.14.0, which can be installed by "**pip install tensorflow==1.14.0**". 

# Running
In the Matlab code, run each block in "main.m" to obtain reproducible results in the paper. In the Python code, run "fmnist.py" to get results in Table VI in the supplement. The results may fluctuate to some extent for each run.
