# D4Fourier
Julia code: Add on to RadiiPolynomial.jl for D4-symmetric Fourier sequences.
# Computer assisted proofs with symmetry, reduced set of Fourier indices



Table of contents:


* [Introduction](#introduction)
* [Laplacian Operator](#laplacian)
* [Utilisation and References](#utilisation-and-references)
* [License and Citation](#license-and-citation)
* [Contact](#contact)



# Introduction

This Julia code is an add to the package [RadiiPolynomial](https://github.com/OlivierHnt/RadiiPolynomial.jl). It constructs the mathematical objects (spaces, sequences, operators,...) usually found in the aforementioned package for D4-symmetric functions. More specifically, it performs computations on Fourier series indexed on the set 

$$J_{\mathrm{red}}(D_4) = \biggl\{n=(n_1,n_2) \in \mathbb{Z}^2, 0 \leq n_2 \leq n_1 \biggr\}$$

The computations can be made rigorous by using the package [IntervalArithmetic](https://github.com/JuliaIntervals/IntervalArithmetic.jl).


# Laplacian Operator

In [RadiiPolynomial](https://github.com/OlivierHnt/RadiiPolynomial.jl), derivative operators are provided. When using $D_4$-symmetric sequences, the action of differentiation does not necessarily yield another $D_4$-symmetric sequence. For simplicity, we provide the Laplacian operator as it's action on a $D_4$-symmetric sequence remains in $D_4$. More specifically,

$$Laplacian(n) = \frac{\partial^n}{\partial x_1^n} + \frac{\partial^n}{\partial x_2^n}$$
 
 # Utilisation and References
 
 The code is build using the following packages :
 - [RadiiPolynomial](https://github.com/OlivierHnt/RadiiPolynomial.jl) 
 - [IntervalArithmetic](https://github.com/JuliaIntervals/IntervalArithmetic.jl)
 
 By installing [RadiiPolynomial](https://github.com/OlivierHnt/RadiiPolynomial.jl), you automatically install [IntervalArithmetic](https://github.com/JuliaIntervals/IntervalArithmetic.jl). Hence, by installing the former, you can use the $D_4$Fourier sequence structure.

 More details on using the operations can be found in the documentation for [RadiiPolynomial](https://github.com/OlivierHnt/RadiiPolynomial.jl).
 
 # License and Citation
 
  This code is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
  
If you wish to use this code in your publication, research, teaching, or other activities, please cite it using the following BibTeX template:

```
@software{$D_4$Fourier.jl,
  author = {Dominic Blanco},
  title  = {D4Fourier.jl},
  url    = {https://github.com/dominicblanco/D4Fourier.jl},
  note = {\url{https://github.com/dominicblanco/D4Fourier.jl},
  year   = {2024},
  doi = {10.5281/zenodo.10966934}
}
```
DOI : [10.5281/zenodo.10966934](https://zenodo.org/records/10966934) 


# Contact

You can contact me at :
dominic.blanco@mail.mcgill.ca
