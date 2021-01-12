# Chapter 01: Python

- [Chapter 01: Python](#chapter-01-python)
  - [Environment Set-up for Machine Learning](#environment-set-up-for-machine-learning)
  - [Set up Machine Learning Enviroment](#set-up-machine-learning-enviroment)
  - [Python Review](#python-review)
  - [R Review](#r-review)

## Environment Set-up for Machine Learning

- Web-based
  - [Google Colab](https://colab.research.google.com/)
    - [use GPU/TPU in Colab](https://medium.com/deep-learning-turkey/google-colab-free-gpu-tutorial-e113627b9f5d#:~:text=Google%20Colab%20is%20a%20free,TensorFlow%2C%20PyTorch%2C%20and%20OpenCV.)
- Local Set-up
  - [gcc](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)/g++
    - GNU [make](https://www.gnu.org/software/make/manual/make.html)
  - [Conda](https://docs.conda.io/en/latest/)
    - use Miniconda
    - environmental variables configured in ~/.bashrc
  - R
    - conda install r-essentials r-base
  - [Docker](https://docs.docker.com/)
    - [NVidia Docker](https://github.com/NVIDIA/nvidia-docker) to use GPU in Docker
  - [CUDA](https://docs.nvidia.com/cuda/cuda-installation-guide-linux/index.html)
    - tips
      - disable nouveau
      - restart system and enter physical shell
      - shut down XServer
      - download runfile from official websire
      - add -noopengl-libs in your commands
    - installing CUDA must be done very carefully
  - [Jupyter](https://jupyter.org/)

## R Review

[Advantages of R](https://www.datacamp.com/community/tutorials/r-or-python-for-data-analysis)

- Stasitical Packages in CRAN
  - splines
  - linear models
    - automatically tell categorical variables, no one-hot needed
    - gam based lasso for variable selection
  - general modeling
    - no "model not recognized" problem
    - combine model with spline, L1 loss, etc
    - complex formulas
- Data Science Packages
  - [dplyr](https://dplyr.tidyverse.org/) and tidyverse
  - ggplot2
  - miss
    - for missing values
    - for nonlinear transformations

## Python Review

- python error handling
- python functional programming
  - [Monad](https://github.com/jasondelaat/pymonad.git)
  - lazy evaluation
  - multi-thread
- python variables and assignment
- pythonic class basics
    - https://docs.python.org/3/library/operator.html
    - https://www.geeksforgeeks.org/operator-overloading-in-python/
    - magic list
    - decorator (data class, etc)
- python logging
- data class, sphinx
    - https://www.sphinx-doc.org/en/master/
- syntactic sugar
    - decorator (package)
        - func_tools, partial
        - design pattern
- functional programming
    - map reduce
    - scan
    - associate scan


- Colab and Jupyter Notebook. 
- How to set up a deep learning working environment.
- A brief review of Python and R.
- Exceptional handling with an emphasis on functional programming techniques.
- Functional programming in Python.
- Decorator.
- Dataclass and docstring. 