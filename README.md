# Installation
To run the Jupyter Notebook, please install the following:

Anaconda (https://www.anaconda.com/distribution/), which already consists of Jupyter Notebook, NumPy, pandas, seaborn, matplotlib, SciPy, scikit-learn.

Jupyter Notebook (https://jupyter.org/install.html)

There are several packages and/or libraries that need to be installed to run the notebook:

Pandas (https://pandas.pydata.org/pandas-docs/stable/getting_started/install.html)

NumPy (https://docs.scipy.org/doc/numpy/user/install.html)

Seaborn (https://seaborn.pydata.org/installing.html)

Matplotlib (https://matplotlib.org/users/installing.html)

SciPy (https://www.scipy.org/install.html)

Scikit-learn (https://scikit-learn.org/stable/install.html)

# Data
There are several datasets we provide:

1. test2: The dataset measured the contact angle including tangent angle , ellipse method , circle method by ImageJ.
1. data: The dataset includes the ellipse method and circle method angles.
2. Contact Angle Images-20231122 the initial image of the droplet on the surface
3. Measured: Images analysed by imageJ.

# Workflow
There is a jupyter notebook files called Zisman plot codes.ipynb.
The workflow is the following:
1. We start by loading the data, choose y as the circle method contact angle and ellipse method contact angle.
1 .We choose the surface tension of ethylene glycol, toluene, water as our x
1. Use linear curve fitting method(The least squared method) to fit the curve.
1. Get the critical surface tension by calculate the value when y=0.

# Author
Bo Li(QMUL, undergraduate)
