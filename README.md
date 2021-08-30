# Computing for Research Bootcamp 2021 - Materials

This repo contains the scripts and data for the 2021 DSEER "Computing for Research" bootcamp. It will be updated frequently with new materials and solutions to past exercises.

## TO-DO List:
1. Check that your environment is [setup correctly](#environment-setup-instructions)
  - [python](#python)
  - [Github](#github-and-git)
  - [package manager](#pip--conda)
  - [Jupyter notebook](#jupyter-notebook)
  - [libraries](#libraries)
2. Create a [git repository](#creating-a-git-repository) on your Desktop
3. [Check](#check-that-everything-works) that you've correctly done steps 1 and 2 by running the `welcome.ipynb` notebook
4. Read through the [syllabus]()

---

## Environment Setup Instructions

We expect many of you already have many of the tools we will use in this course installed, but please double check each of them. For your reference, they are:
- python 3.6.x or higher
- a Github account + local installation of git
- pip/pip3 and/or conda
- Jupyter notebook
- libraries: numpy, matplotlib, pandas. 
  - other libraries will be installed via pip/conda as necessary during class

### python

We recommend using Anaconda to install python, as the conda installer will also automatically configure many of the common python packages and libraries.

To check your python installation: open your command line of choice (`cmd.exe` on Windows, "Terminal" on MacOS/Linux) and type `python --version`. Ensure that you are running Python 3.6 or higher.
- depending on your installation -- especially if you are using a Mac -- this may return Python 2.6 or 2.7. if this is the case, try `python3 --version`
- if this command returns an error, or your python version is earlier than 3.6, follow the instructions linked [here](https://carpentries.github.io/workshop-template/#setup) to install Anaconda + python

### Github and git

If you do not already have a github account, you should create one [here](https://github.com/join). We recommend using your UChicago email -- students get a Pro account for free. A Pro account is not necessary for this bootcamp, but you may find it helpful for your research in the future.

You can check if git is locally installed by typing `git --version` into your command line. If you do not have git installed, follow the instructions linked [here](https://carpentries.github.io/workshop-template/#setup). 

NOTE: if you are on Windows, follow the link above and also install git bash. This is a command line tool that allows you to use bash/zsh commands.

### pip + conda

pip/pip3 and conda are package managers -- installation wizards, even. They will allow you to easily install python libraries (homebrew is another popular one, but more difficult to use). If you installed python with Anaconda, both come pre-installed for you. If you did not use Anaconda to install python (or if you have python but don't remember how you installed it), check your pip3 version by typing `pip --version` or `pip3 --version` into the command line.
- if this doesn't work, follow the instructions [here](https://packaging.python.org/tutorials/installing-packages/) to install pip
- if this does work, update pip by typing `pip3 install --upgrade pip` into the command line
  - depending on your local permissions, this command may fail due to administrator preferences. if this is the case, type `sudo pip3 install --upgrade pip` into the command line, and type the password you use to log in to your computer when prompted

if you have Anaconda but did not just install it, update conda to the latest version by typing `conda update conda` into the command line.

### Jupyter notebook

We will be using Jupyter notebooks for this bootcamp rather than using a text editor to write our scripts. If you just installed Anaconda, then Jupyter notebook comes pre-installed. To check if you have it installed, type `jupyter notebook` into the command line. If the Jupyter interface opens in your web browser, then it is installed. Otherwise:
- install Jupyter with pip by typing `pip3 install jupyter` into the command line (use `sudo` if you run into trouble with permissions)

### libraries

Once again, if you have just installed python through Anaconda, these libraries have already been added for you. Otherwise, type `pip3 list` into the command line to list all python libraries you have installed on your computer. Ensure that `numpy`, `matplotlib`, and `pandas` are all listed.
- to install a package you are missing: `pip3 install [package]`
- to update a package you already have installed: 
  - conda: `conda update [package]`
  - pip: `pip3 install [package] --upgrade`
  - please make sure that these packages are up-to-date

---

## Creating a git repository

This will walk you through creating a git repository on your Desktop through your command line. Note: if you are using Windows, you will want to use the git bash command line.

1. Open your command line, and change directories to your Desktop.
  - to see your current directory, type `pwd`
  - to change directories, type `cd [directory]` 
  - if you would like to see all folders in the current directory, type `ls -d */`
2. Type `git clone https://github.com/NRT-DSEER/computing_for_research_2021.git`
3. Type `cd computing_for_research_2021` to move into the new folder

---

## Check that everything works

0. If you just completed step 3 above, skip this step. Otherwise, open your command line and cd into the git repository for this class
1. Type `jupyter notebook`. Your terminal will print a bunch of stuff, and then the Jupyter interface should open in your default browser
2. In this browser tab, click on the file named `welcome.ipynb` and follow the instructions there -- if everything worked, you're ready to go!

--- 

## Syllabus 

update this later
