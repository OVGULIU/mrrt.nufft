NUFFT
=====
High performance NUFFT based on a port of Jeff Fessler's Matlab NUFFT code
from his [image reconstruction toolbox](https://web.eecs.umich.edu/~fessler/code/).


Basic Usage
===========
TODO

Documentation
=============
TODO

Required Dependencies
---------------------
- [numpy](https://github.com/numpy/numpy)
- [scipy](https://scipy.org)
- [pyir.utils](https://github.com/grlee77/pyir.utils)

Recommended Dependencies
------------------------
- [matplotlib](https://matplotlib.org)  (for plotting)
- [pyFFTW](https://github.com/pyFFTW/pyFFTW) (enable faster FFTS than numpy.fft)
- [pyir.cuda](https://github.com/grlee77/pyir.cuda)  (code to support the GPU implementation is here)