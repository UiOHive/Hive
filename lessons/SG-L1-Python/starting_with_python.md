---
layout: page
title: Getting started with Python for Science
text: How to get started with Python for 
link: 
visible: true
tags:
  # languages
  - Python
  # levels
  - beginner
---

<!-- change visible to true if you want it on the site -->
<!-- remove any tags listed above that are not relevant -->

# Getting started with Python

 - **Authors**: Simon Filhol
 - **Research field**: Geosciences, programing
 - **Lesson Topic**: How to set up your environment to work with Python

## What is Python?

Not sure Python still need to be introduce yet another time online, but to keep it short, Python is a programing language that is interprated. This means that a Python code does not need to be compiled to be executed. Python was designed by XXX in 19XX with the purpose to be an object-oriented language. 

Today, because Python is free, well documented, and widely recognized for its syntax clarity, it is used in a wide variety of sectors. From Python, a programmer can interact with the computer, the internet, data, or program embeded device for IoT applications. Just like Lego, Python allows to build program brick by brick. Over the years, users wrote libraries for various purposes. Some famous ones for scientific analytics are [Numpy](), [Scipy](), or [Matplotlib]().


## How to install it?

The first step before starting programing is to get your Operating System (OS) ready. On most OS Python is already installed, and you can easily check it by opening a terminal and type `python`. This should open the python console. There you can type `1+1` and immediately get a result. You can exit the console by typing `exit()`. THowever, you should not use Python packaged with your OS as it risks to bring instabilities to your system. A simple way to deal with this is to use virtual environments.

From the website [Anaconda](), you can download Conda which will help you installing and managing virtual environments. Following their documentation you can then create as many Python environments as you want and not interfere with your OS. 

Then comes the question of which Python version to choose. Well, unless you specifically need an older version, it is recommended to get the latest verion of Python 3. There are many discussion on the topic online if you are interested to learn more about it, but a safe bet is to use Python 3. 

**
1- Ok, then download and install Conda on your machine
2- create a virtual environment using conda
3- install libraries needed for your project
**

## Which libraries to use for data analytics?

There are many libraries out there. Some of the most commonly used in, for instance geophysics, are:
	- Numpy for working with multi-dimensional data and linear algebra
	- Matploltib for plotting
	- Pandas for working with tables and timeseries analysis
	- Gdal for working with spatial dataset
	- Scipy for having mathematical methods ready to use on your numpy data
	- Statmodels for statistical analysis
	- Scikit-learn for statistical analysis and machine learning
	- Scikit-image for image analysis

By combining these toolboxes, you can now read, filter, prepare, process, and plot your data. 

## How to write code?

To write code, you can use a simple text editor, and call the file like *filename.py*. However there are many editor more geared towrads coding, and some specifically for conding in Python. In many instances it will depend on your OS. Some of them are:
- Pycharm (all OS)
- Sublime (all OS)
- Notepad++ (windows only)
- Atom (all OS)
- Vim
- Emacs

## An example

Here is an example of a script you can write in a file called *myscript.py*. It is assumed that you have installed python and the libraries Pandas and Matplotlib. 

```Python

# Here we first load the libraries we use to open and analyse the data
import pandas as pd 
import matplotilb.pyplot as plt

# Then we open data, and store the data in the computer memory as a pandas DataFrame object
df = pd.DataFrame()


# Prepare data


# Process data


# Plot results
plt.figure()


plt.show()

```

Then open your terminal where you have saved the file (or command line on Windows), and type `python myscript.py`. You should see the script being executed, and plots coming to your screen!



