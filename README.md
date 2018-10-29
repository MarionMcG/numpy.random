# Semester 2: Programming for Data Analysis
## Investigate the numpy.random package

In this repository you will find my investigation of the numpy.random package. The body of my work in contained in the Jupyter notebook numpy-random.ipynb; including all code, explanations and references. 

In this file you will find:
1. Information on how to download and save the numpy-random.ipynb notebook.
2. Instructions on how to open the notebook on your machine.
3. How to run code cells in an open ipynb notebook.
4. My approach to this assignment, and evaluation of it's success.
5. Areas of Difficulty.
6. A note on my References.

 
### 1. Downloading an ipynb file from Github
**Windows**
* Click to open the file "numpy-random.ipynb" above.
* Right click on Raw, and select Save link as
* Choose the directory you want to save the file to. You may change the name of the file but keep the extension as .ipynb.

### 2. Opening an ipynb file on your machine
* Open a terminal, such as Command Prompt. I will be using [Cmdr.exe](http://cmder.net/), but it doesn't matter which command line interpreter you use. 
* First, check if Jupyter is installed on your machine. Type the command, 'jupyter -- version' to determine this, and also to see which version is installed on your machine. You should also ensure Python is on your machine, by entering the command 'python --version'.

![](images/openipynb1.jpeg)

* If Jupyter Notebook is **not** installed, you should download [Anaconda](https://www.anaconda.com/download/) which supports Jupyter notebook files, and Python code. 
* Once Jupyter is installed, type the command, 'jupyter notebook' to open a static webpage displaying the folder you're currently in. You may need to copy and paste the URL (highlighted below) that appears on the command line, if a webpage doesn't automatically open. 

![](images/openipynb2.JPG)

**NOTE:** When opening Jupyter notebook, ensure your downloaded ipynb file is in a subdirectory of the folder you are in. You may use the cd/ command to go to the top of your directory, to ensure this is the case. Alternatively if you're familiar with commands, you may use the 'cd' command to navigate to the directory containing your notebook.
* From the webpage, navigate to the folder containing your ipynb file and click to open in a new tab. 

### 3. Running code from an ipynb file

### 4. Appproach and Evaluation 
My approach was to work my way through each of the functions and classes included in the numpy.random package. I planned to:
* Examine all or most of the random number generators, listed under the heading Simple Random Data
* Examine some of the functions which could be used for sampling datasets, listed under the heading Simple Random Data
* Examine functions which could be used to shuffle variables, listed under the heading Permutations. 
* Examine five distribution
  1. Normal 
  2. Uniform
  3. Binomial
  4. Maybe CHisquare
  5.
* Investigate tools for seeding random number generators

**Evaluation**

Given the amount I've using numpy.random, I should have imported as random, or a suitable acronym. I did need the whole numpy package as I used it to sum and round values as well, but in the interests of efficiency I would import my libraries differently in futre. 

### 5. Areas of Difficulty
* Shuffle() - I encountered difficulty in my investigations of shuffle() and it's differences when compared to permutation(). This arose as I misunderstood what the documentation meant when it said that the function shuffled the data in place. 
### 6. A note on References
* In my notebook, I have referenced websites and journals accessed during the course of this assignment. 
* Due to my own background in Mathematics, there are ver few references into the theory of the distributions examined. This is because I did not consult any other resources in my examination of uniform, normal or binomial distributions. I already have extensive experience with them, and relied on my own theoretical understanding. 
