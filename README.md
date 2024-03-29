# Public Health Data Science - Intro to Neural Networks

This is the `README` file for the **Introduction to Machine Learning - Neural Networks** component for the [Digital Public Health](https://digital-public-health.u-bordeaux.fr/) program at the University of Bordeaux.

If you already have Anaconda, ensure that you have completed the installation of required Python packages [below](#installation-of-python-packages). 

## Installation of Anaconda

1. Go to the Anaconda website [here](https://www.anaconda.com/distribution/).
2. Click on Linux tab and download the Anaconda installer for **Python 3.7**
3. Open Terminal and execute the following commands:

```
cd ~/Downloads
chmod +x Anaconda3-2019.07-Linux-x86_64.sh
./Anaconda3-2019.07-Linux-x86_64.sh
```

:exclamation: You may want to reset your Terminal window by simply restarting it.

## Installation of Python packages

Similarly as in R, functionalities that we are interested in are often already available in packages. All that is required is that we install them and we are able to do so using Anaconda. 

In Python, it is a good habit to create a virtual environment for your packages. Although this is optional, this is good practice since packages are frequently updated. Having multiple projects using different versions of a same package could raise unwanted issues.


```
conda create -n yourenvname python=3.7 
conda install -n yourenvname numpy pandas matplotlib tensorflow keras scikit-learn
```

#### Brief explanation of every packages' functionalities:
- ```numpy```: Used for vector and matrix computations, especially for data handling.
- ```pandas```: Used to load data nicely in data frames. Somewhat equivalent to ```data.frame``` in R.
- ```matplotlib```: Data visualization and plotting.
- ```tensorflow```: Machine Learning library maintained by Google that facilitates the implementation and training of neural networks.
- ```keras```: Package built on top of ```tensorflow```; more user-friendly and easier to understand.
- ```scikit-learn```: Package containing other statistical or machine learning models (e.g. Logistic/Linear Regression, Random Forests, etc.).

## Downloading these files

There are two options if you wish to download the files here or from any GitHub repository:

1. Click the green button "Clone or download" and then "Download as ZIP"
2. (Preferred) Open Terminal and execute the following command:
```
git clone https://github.com/LarryShamalama/PHDS-Intro-to-NN
```

## All set! :blush:

Once you've cloned my repository and successfully installed Anaconda (and Jupyter notebook by extension), open Terminal and type
```
jupyter notebook
```
