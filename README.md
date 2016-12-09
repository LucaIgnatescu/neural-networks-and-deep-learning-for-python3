#Introduction
This repository contains code samples for Michael Nielsen's book [Neural Networks and Deep Learning][1].

The code is modified or python 3.x. The original code is written for Python 2.6 or Python 2.7 and you can find the original code at [github][2]. The origin purpose for which I create this repository is to study Neural Network and help others who want to study it and need the source code. I'm quite willing to discuss it with anyone.
##Installing python3.x
You should install [python interpreter][3] on your computer before you clone this repository. The latest version of python now is python3.5.2 which is intalled on my computer. The steps of intalling python are very easy and you can use [Google][4] if you have any question about it.
##Installing NumPy and SciPy
It is a little difficult for python3.x to install [NumPy][5] and [SciPy][7]. 

Numpy is the fundamental package for scientific computing with python. it contains among other things:
* a powerful N-dimensional array object
* sophisticated(broadcasting) funcions
* tools for integrating C/C++ and Fortran code
* useful linear algebra, Fourier transform, and random number capabilities

The NumPy installation package can be found [here][6]. The names of intallation packages are follow the following rules:

	cpxx_OperatingSystem_The architecture of CPU

cpxx means the interpreter of python whose verison is python x.x is written by C. OperatingSystem can be Macoxsx,linux or win. The architecture of CPU can be x86, amd64 or i686.

SciPy is open-source software for mathematics, science, and engineering. The SciPy library depends on NumPy.The SciPy library is built to work with NumPy arrays, and provides many user-friendly and efficient numerical routines for numerical integration and optimization. The rule of name of SciPy is similar to that of Numpy.

So choose the version which is suitable for your computer and the interpreter of python.

##Modifying code samples for python 3.x
Now we could make some changes for code samples in order to run our code samplesthrough python 3.x interpreter after some fundamental packages has been installed. The differences between files for python 2.x and python 3.0 will be listed below and some descriptions have been added for this changes.

###[mnist_loader.py][8]

[1]: http://neuralnetworksanddeeplearning.com/
[2]: https://github.com/mnielsen/neural-networks-and-deep-learning
[3]: https://www.python.org/downloads/
[4]: https://www.google.com
[5]: http://www.numpy.org/
[6]: https://pypi.python.org/pypi/numpy
[7]: https://pypi.python.org/pypi/scipy
[8]: ./mnist_loader.py
