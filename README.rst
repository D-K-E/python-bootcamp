===========================================================================
Y(et) A(nother) (Introduction) to P(rogramming) with (Functional) P(ython)
===========================================================================

As the title states quite explicitly this is just another introduction to
programming. The language of choice is Python 3.
Our paradigm of choice is functional paradigm. I believe that composing
functions is an easier concept to grasp, and reproduce. This choice is
certainly biased, relative, etc. 
If you insist on learning programming from an object oriented perspective,
there are a lot of other tutorials/books available online. However you might
still want to checkout first few sections, since first steps and general
building blocks for programs are same for all paradigms anyway.

Installing Python
==================

We use the package manager conda for isolating work spaces. We are
going to miniconda distribution.

You can download it from 
`here <https://docs.conda.io/en/latest/miniconda.html>`_.

We are going to use python 3.

Once you have downloaded, and run the installer.

- Make sure you have an internet connection.
- Open your terminal, or anaconda prompt if you are on windows.
- Write the following and press enter:

  - :code:`conda --version`: you should see something like :code:`conda 4.1.8`
  - :code:`conda create -n yapp`
  - :code:`conda activate yapp`
  - :code:`conda install python=3`
  - :code:`conda install jupyter`
  - :code:`conda update --all`

- Download or clone this repository to a location of your choice.

  - Unzip the repository if you had downloaded it.

- :code:`cd PATH_TO_REPOSITORY`
- :code:`cd yapp`

- To start with first lesson:

  - :code:`cd course-01`
  - :code:`jupyter course01.ipynb`
  - Follow the instructions in the notebook
