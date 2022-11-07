# StatMethods2022
Humboldt Universität zu Berlin - Statistical Methods 2022 (Prof. Dr. Marek Kowalski). Examples covered by Alice Townsend.

## Getting started

### 0. Clone and update this repository

To get all data included in this repository, open a terminal, navigate to the directory you want to work in and execute
```
git clone https://github.com/aotownsend/StatMethods2022.git

```

This will create a directory `StatMethods2022` in the current directory. \
Any updates that will be posted can be downloaded by simply executing
```
git pull
```

For the Linux/OSX users, it is best to use the git command lines:
- **git clone** to copy a github repository
- **git add** to add a file change to be committed
- **git commit -m "message here"** to commit a change
- **git push** to push the commit to the repo
- **git pull** to pull any new changes from the repo

For Windows users (and Unix users who do not like command lines...), see Desktop Github: https://desktop.github.com.

### 1. Installing `Python` / `conda`
`Python` is the programming language we will be using. If you're not familiar with `Python` basics there are plenty 
of introductions, see e.g. https://www.learnpython.org.

If you do not have a `Python` instance set up on your computer, we recommend installing `conda`. `conda` does not only 
provide the interpreter for `Python` but is also a package manager, that allows to easily install ad-on packages that 
we will need. You can find more info here: https://docs.conda.io/projects/conda/en/latest/index.html \
We recommend installing the lightweight `conda` called `Miniconda`: https://docs.conda.io/en/latest/miniconda.html


### 2. Creating a virtual environment
Having installed `conda` you can set up a virtual environment that acts as a closed of programming environment and does 
not interfere with any other programming projects. 
In your terminal type
```
conda create --name statmethods python==3.9
```
You will have to install the packages manually as described in 3.

To activate the environment type
```
conda activate statmethods
```
If you want to leave the environment do
```
conda deactivate
```


### 3. Installing packages separately

You can install all packages via `pip`. The packages you can start with are `numpy`, `matplotlib`, `jupyterlab`, `scipy`, `pandas`, and `astropy`.
Make sure your environment is activated and execute
```
pip install <package name here>
```


### 4. Running `jupyter`

The `jupyter notebook` is an interface to the interactive `python` called `IPython`. 
Notebook files have the file extension `.ipynb`. To start it, activate your environment (if you haven't already) and run
```
jupyter notebook
```

This opens the `jupyter notebook` webpage in your browser. You can now browse for a Notebook file in the file browser on the left
and open it via double click.
