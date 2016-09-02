# Random numbers : characterization and generation #

* [statistics](https://github.com/bos/statistics) : This library provides a number of common functions and types useful in statistics. We focus on high performance, numerical robustness, and use of good algorithms. Where possible, we provide references to the statistical literature.

The library's facilities can be divided into four broad categories:

** Working with widely used discrete and continuous probability distributions. (There are dozens of exotic distributions in use; we focus on the most common.)

** Computing with sample data: quantile estimation, kernel density estimation, histograms, bootstrap methods, significance testing, and regression and autocorrelation analysis.

** Random variate generation under several different distributions.

** Common statistical tests for significant differences between samples.
* [mwc-random](https://hackage.haskell.org/package/mwc-random) : This package contains code for generating high quality random numbers that follow either a uniform or normal distribution. The generated numbers are suitable for use in statistical applications. 
* [mwc-probability](https://hackage.haskell.org/package/mwc-probability) : This implementation is a thin layer over mwc-random, which handles RNG state-passing automatically by using a PrimMonad like IO or ST s under the hood.