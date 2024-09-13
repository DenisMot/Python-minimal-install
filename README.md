# Python-minimal-install

A minimal Python environment for reproducible research in human movement sciences.

### Minimal install 
The minimal requirements to start with a human movement data analysis project are :  
- `python` : the language 
  - `numpy` and `matplotlib` : the python packages for scientific data analyses
  - `ipykernel`: to run jupyter notebooks mixing python and markdown blocks 
- `VSCode` : the development environment (editor, debugger...)  
- `conda` : the package management system to manage your python environment 

You will need approximately 2.5 GB of free space on your hard drive to install all the needed tools.

#### Install python 
- Install `miniconda` to get a minimal python install (https://conda.io/miniconda.html). 
    - Download the **Latest Miniconda Installer** appropriate for your computer (Mac users: prefer the `pkg` version)
    - Install `miniconda`, accepting all defaults 
- Check you installation 
    - Open a shell window (shell is here a generic term for `Terminal` on Macs and `Powershell` on Windows)
        1. The shell prompt should look like: 
        `(base) `userName`@`computerName` `currentDirectory `%`  
        (e.g., `(base) denismottet@MacBook-Pro-de-Denis % `  )  
        The prefix `(base) ` indicates that conda has activated the `base` environment automatically (default miniconda behavior). 

        1. At the shell prompt, ask where is the python software located  
        i.e., type  `which python` (Terminal) or `where python` (Powershell). The answer should be :   
        youHomeDirectory`/miniconda3/bin/python `  (Terminal)   
        youHomeDirectory`\miniconda3\bin\python `  (Powershell) 
- If you do not get the previous results :
    - double check the options you selected when installing `miniconda`
    - double check the version of the installer you have chosen 

### Install VSCode 
VSCode is a development environment well suited for python. 
- Install `VSCode` 
    - download the appropriate version for you computer from https://code.visualstudio.com/
    - install `VSCode`, accepting all defaults
- Open `VSCode` and install the required extensions for python
    - `VS Code Python extension`, to edit,run and debug the python code. 
    - `Jupyter Extension for Visual Studio Code`, to edit,run and debug the jupyter notebooks. 

### Install the required python packages
The goal is to install the packages in the `base` environment (i.e., your default python environment).  
Open a shell window to run the install commands
- install numpy, to manipulate data series and matrices
    - `conda install numpy`
- install matplotlib, to plot data
    - `conda install matplotlib`
- install ipykernel and nbformat, to run jupyter notebooks in VSCode
    - `conda install ipykernel nbformat`

### Install GitHub Desktop
GitHub Desktop is an easy front end to the Git version control system. 
- Install `GitHub Desktop` 
    - download the appropriate version for you computer from https://github.com/apps/desktop
    - install `GitHub Desktop`, accepting all defaults

### Create a GitHub account (for you as a student)
Github is a cloud-based platform that lets you track and control changes to your code. As a student, you get free pro access to some very useful tools. 

- go to https://github.com/ and sign up
  - e-mail: your student's email
  - username: your First name + the first 3 letter of your Familly name + `_student` (e.g. `DenisMot_student`)
  

