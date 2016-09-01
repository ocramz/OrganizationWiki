# Existing libraries for numerical integration #

## Markov Chain Monte Carlo ##
* [flat-mcmc](https://hackage.haskell.org/package/flat-mcmc) Painless, efficient, general-purpose sampling from continuous distributions.
* [speedy-slice](https://hackage.haskell.org/package/speedy-slice) This implementation of the slice sampling algorithm uses lens as a means to operate over generic indexed traversable functors, so you can expect it to work if your target function takes a list, vector, map, sequence, etc. as its argument.
Additionally you can sample over anything that's an instance of both Num and Variate, which is useful in the case of discrete parameters.
* [hasty-hamiltonian](http://hackage.haskell.org/package/hasty-hamiltonian) Gradient-based traversal through parameter space.

# Numeric Processing #

* [ad](https://hackage.haskell.org/package/ad): Automatic differentiation
* [repa](https://hackage.haskell.org/package/repa): Fast stencil operations on arrays
* [accelerate](https://hackage.haskell.org/package/accelerate): gpu-based computation
* [vector](https://hackage.haskell.org/package/vector): high-performance arrays
* [hmatrix](https://hackage.haskell.org/package/hmatrix): BLAS/LAPACK wrapper
* [eigen](http://hackage.haskell.org/package/eigen): bindings to C++ Eigen library
* [hblas](https://hackage.haskell.org/package/hblas): supports more dense matrix formats
* [bed-and-breakfast](http://hackage.haskell.org/package/bed-and-breakfast): fast matrix operations in native haskell

