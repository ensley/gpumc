# gpumc

This package is a wrapper around a single function, mc(). This function takes a vector of observations from a Gaussian process and a vector of random samples from a spectral density and estimates the covariance matrix between the observations.  The covariance matrix is estimated elementwise, and can be pretty large, so the operation is sped up with parallel computing on a GPU. You must have a CUDA-enabled GPU on your machine to install this package!
