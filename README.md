# tasks-machine-learning
## 52954 Machine Learning &amp; Statistics Tasks


<p align="middle">
  <img src="img/python.jpg" width="100" />
</p>

## Description

This README describes work done for the Machine Learning and Statistics module tasks, due 18 December 2020.

We have been asked to complete four tasks:
- Write a Python function called ```sqrt2``` that calculates and prints to the screen the square root of 2 to 100 decimal places. Your code should not depend on any module from the standard library or otherwise (no ```import``` statements allowed).
- Use a Chi-squared test to analyse whether two categorical variables are independent. Use ```scipy.stats``` to analyse the data provided in the contingency table [here](https://en.wikipedia.org/wiki/Chi-squared_test), and verify that the Chi-squared value based on this data is 24.6.
- Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S. STEDV.p uses this calculation ```np.sqrt(np.sum((x - np.mean(x))**2)/len(x))``` where ```x``` is a ```numpy``` array. STDEV.S has ```len(x)-1``` in the denominator. Research the functions and perform a simulation demonstrating that STDEV.S is a better estimate for the standard deviation of a population when performed on a sample.
- Use ```scikit-learn``` to apply k-means clustering to Fisher's Iris data set. Explain how the code works, how accurate it might be, and how it could be used to make predications of Iris species.

## Getting started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- [Anaconda distribution of Python](https://www.anaconda.com/distribution/)
- [Python Software Foundation](https://www.python.org/)
- [Project Jupyter](https://jupyter.org/)
- [matplotlib: Python plotting library](https://matplotlib.org/)
- [NumPy](https://numpy.org/)
- [SciPy](https://www.scipy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)

### Installing
Download and install the Anaconda distribution of Python from the link above. The other packages (Jupyter notebook, Pandas, matplotlib, NumPy, and Scikit-learn) come as part of that distribution.

### Project repository
This project is hosted on [GitHub](https://github.com/) at 
https://github.com/elizabethdaly/tasks-machine-learning

The analysis takes the form of a single Jupyter notebook of filename **tasks-machine-learning.ipynb**

### Instructions for cloning the repository
A repository on GitHub exists as a remote repository. You can clone this repository to create a local copy on your computer by following these instructions:
1. On GitHub, navigate to the main page of the repository https://github.com/elizabethdaly/tasks-machine-learning
2. Under the repository name, click Clone or download.
3. Choose "Clone with HTTPS".
4. Open a terminal on your machine. Change the current working directory to the location where you want the cloned directory to be made.
5. Type git clone, and then paste the URL you copied in 2 above.
```
git clone https://github.com/elizabethdaly/tasks-machine-learning
```
6. Press enter to clone the repository to your machine.

## Static version of the notebook
Alternatively, one can view a static version of the notebook using [Jupyter Nbviewer](https://nbviewer.jupyter.org/). Enter the GitHub url to view the file.

```
https://github.com/elizabethdaly/tasks-machine-learning/blob/master/tasks-machine-learning.ipynb
```

## Additional files
All images intended for inclusion in this README or the Jupyter notebook are located in the **img** subdirectory of this repository.

## Author
Elizabeth Daly for HDip in Data Analytics 2019/2020.

## Licence

This project is licensed under the GNU General Public License v3.0 - see the LICENSE.md file for details.
