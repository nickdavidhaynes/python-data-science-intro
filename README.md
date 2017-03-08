# Fundamentals of Data Science with Python

Welcome! This is a class being taught for [Girl Develop It RDU](https://www.girldevelopit.com/chapters/raleigh-durham).

The rough syllabus (subject to change) is:

- Week 1: Overview of Python
- Week 2: How computers store and process data, using NumPy to process data quickly
- Week 3: Exploratory data analysis
- Week 4: An intro to building models

## Getting started

### Step 1: Get git
The first thing you'll want to do is make sure you have git installed on your machine. Git is a program that software engineers and data scientists use to keep track of the progress they make on software projects and collaborate with teammates. In this class, we'll use git to keep track of the course materials and post solutions.

#### Mac OS
To check to see if you already have git installed, open a terminal window and type `which git`. If you already have git, you'll see a filepath printed to the screen. If nothing is printed, it means you don't have git installed.

The easiest way to install git is with [homebrew](http://brew.sh/). Homebrew is a package manager that makes it easy and super-fast to download and install common programs that developers use. Again, check whether you already have homebrew installed by typing `which brew` in the terminal. If it's not installed, the [brew homepage](http://brew.sh/) has instructions. Once you have homebrew, you can install git by typing `brew install git`.

#### Windows
The nicest way to use git on Windows is with [GitHub for Windows](https://desktop.github.com/). This will install both the command line program and a nice GUI.

#### Linux
Most Linux distributions ship with git. If not, use your package manager of choice (apt, yum, etc).

### Step 2: clone this class repository
When using git, it's often the case that you'll want to grab a version of some code that's stored on a remote server somewhere. This is called *cloning* a repo, and it's what you'll do to get the course materials on to your computer.

#### Command line
If you're on Mac or Linux (or using the Windows command line interface), navigate to the local directory that you want the materials to live in. Then, type `git clone https://github.com/nickdavidhaynes/python-data-science-intro.git`. If you now type `ls` (or `dir` in Windows), you should see a directory called `python-data-science-intro`. This directory contains all of the course materials - congrats!

#### GUI
If you're using the GitHub desktop GUI, follow [these](https://help.github.com/desktop/guides/contributing/cloning-a-repository-from-github-to-github-desktop/) instructions, using the URL `https://github.com/nickdavidhaynes/python-data-science-intro.git`.

### Step 3: Get Python 3
This course will use Python 3. We'll touch on the differences between Python 2 and 3, but suffice to say for now that Python 2 should only be used for legacy reasons.

#### Mac OS and Linux
Your machine already has Python installed. This is called *system Python* and it's generally considered bad practice to use it for development work, since making changes could cause problems with other programs that rely on it (more details [here](https://github.com/MacPython/wiki/wiki/Which-Python)). Instead, we'll install a different version of Python on top of our system Python.

I *strongly* recommend downloading and installing the [Anaconda distribution](https://www.continuum.io/downloads) of Python. Anaconda is a collection of common Python tools used heavily in data science and scientific computing. More importantly, it solves a number of the common Python installation headaches that sometimes give difficulties to beginners. Just download and install the file and *boom, you're done*.

#### Windows
I *strongly* recommend downloading and installing the [Anaconda distribution](https://www.continuum.io/downloads) of Python. Anaconda is a collection of common Python tools used heavily in data science and scientific computing. Some of these tools rely on dependencies that are hard to get working on Windows. Anaconda solves this problem for you by packaging everything you'll need into a single .exe file. Just download and install and *boom, you're done*.

### Step 4: Get the necessary Python packages
Python has a very robust standard library - indeed, part of the Pythonic philosophy is to be "batteries included." Nonetheless, Python is used by so many different communities these days that there's way too much specialized software to ship with every Python download. This specialized code is therefore wrapped up in packages that users can download and use in their projects.

We'll make heavy use of the common Python data science libraries (sometimes called the PyData stack) in this course, in particular, **numpy**, **scipy**, **matplotlib**, **scikit-learn**, and **Jupyter**.

The good news is that if you installed Anaconda as recommended in step 2, you already have the PyData stack! If not, you *might* be able to use `pip`, the standard package manager. Note however that these data science libraries require some special dependencies that not every computer will have (and a Windows machine almost certainly doesn't have). So, seriously - just use Anaconda.

### Step 5: Take a look at the pre-work
All of the notes and exercises for this class will be hosted in [Jupyter](http://jupyter.org/) notebooks. Jupyter notebooks are a crucial part of data science communication and collaboration. A notebook is a file that, when run, opens an internet browser tab. From this tab, you can enter and run lines of code (often Python, but R, Julia, and many other languages have support as well), but also intersperse text and images that tell a better story about what you're doing.

I encourage you to take a look at the week 0 notebook before coming to the first class, especially if you're new to Python. This notebook will give you an interactive environment to familiarize yourself with the basics of Python and should make the first day go a bit more smoothly.

#### Mac and Linux

To run a Jupyter notebook, use the terminal to navigate to the directory where the notebook is stored and run `jupyter notebook`. A browser window with a menu of files - click on `python_essentials.ipynb`. A new tab should open with the notebook content.

#### Windows

You can run a Jupyter notebook either from the command prompt with `jupyter notebook` from the directory where the notebook is stored, or by using the Jupyter app that came with the Anaconda distribution. A browser window with a menu of files - click on `python_essentials.ipynb`. A new tab should open with the notebook content.
