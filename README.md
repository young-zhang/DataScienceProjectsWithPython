


# Data-Science-Projects-With-Python-Second-Edition

This is the repository for the second edition of [Data Science Projects with Python](https://packt.link/a/9781800564480), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all of the supporting files needed for you to work through the course from start to finish.

<a href="https://packt.link/a/9781800564480"><img src="https://static.packt-cdn.com/products/9781800564480/cover/smaller" alt="Data Science Projects with Python, 2nd Edition" height="280px" width="230px" align="right" this.target="_blank"></a> 

## Installing Anaconda and Setting Up an Environment

Install Anaconda by following the instructions at this link: https://www.anaconda.com/products/individual

It is recommended to create an environment in Anaconda to do the exercises and activities in this book, which have been tested against the software versions indicated here. Once you have Anaconda installed, open a Terminal if you're using macOS or Linux, or a Command Prompt window in Windows, and do the following:

# Installing Anaconda
- We will use [Miniconda3 Windows 64-bit](https://repo.anaconda.com/miniconda/Miniconda3-latest-Windows-x86_64.exe)


After installing, open command prompt:

```
conda update -n base -c defaults conda --yes
```

Go to the repo:

```
conda env create -n dspwp2 -f environment.yml
conda activate dspwp2
python -m ipykernel install --user --name dspwp2 --display-name "dspwp2"
```

The last command will install the environment and create a kernel for Jupyter Notebook, which
will be installed into `%APPDATA%\jupyter\kernels`

You can now open Jupyter Notebook and select the kernel you just created.