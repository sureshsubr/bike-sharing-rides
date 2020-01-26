# Bike-sharing-rides
Predict bike sharing rides using Neural Network.  This project is part of the Udacity Deep Learning Nanodegree.

# Introduction

In this project we'll predict bike sharing rides from historical time series bike rental data using Neural Network.  We'll implement gradient descent, backpropagation, training and testing. 

The data comes from the [UCI Machine Learning Database](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset).

# Instructions

1. Set up the Jupyter ipython notebook environment
2. Load and prepare the data using numpy and pandas
3. Build the neural network
4. Train the network using training and validation dataset
5. Test the network for accuracy using test dataset

## 1. Set up the Jupyter ipython notebook environment
## 1.1 Installation

Download Anaconda

|        | Linux | Mac | Windows | 
|--------|-------|-----|---------|
| 64-bit | [64-bit (bash installer)][lin64] | [64-bit (bash installer)][mac64] | [64-bit (exe installer)][win64]
| 32-bit | [32-bit (bash installer)][lin32] |  | [32-bit (exe installer)][win32]

[win64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86_64.exe
[win32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Windows-x86.exe
[mac64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-MacOSX-x86_64.sh
[lin64]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86_64.sh
[lin32]: https://repo.anaconda.com/archive/Anaconda3-2018.12-Linux-x86.sh

**Install** [Anaconda](https://docs.anaconda.com/anaconda/install/) on your machine. Detailed instructions:

## 1.2 Create and Activate the Environment

Please go though this [doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) before you creating an environment.
After that create a environment using following command

```
conda create --name deep-learning
```

Then activate the environment using following command

```
activate deep-learning
```

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, you can create a local version of the project**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/sureshsubr/bike-sharing-rides.git
cd bike-sharing-rides
```

2. Install a few required pip packages, which are specified in the requirements text file.
```
pip install -r requirements.txt
```
Or
```
conda install --yes --file requirements.txt
```

3. That's it!

```
jupyter notebook
```

Once jupyter notebook instance is open follow the remaining steps (2-5) in the ipython notebook called `Predicting_bike_sharing_data.ipynb`.

To exit the environment when you have completed your work session, simply close the terminal window.
