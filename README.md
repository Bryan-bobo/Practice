# Instructions for running the notebook

## Step 1: Install Python and packages
- Mac OS specific installation and setup: https://docs.anaconda.com/anaconda/install/mac-os
- Windows specific installation and setup: https://docs.anaconda.com/anaconda/install/windows
- Linux specific installation and setup: https://docs.anaconda.com/anaconda/install/linux

## Step 2: Follow Anaconda's recommended installation instructions
Make note of the directory where Anaconda lives (you should be prompted to specify this, your home directory is a good choice).

## Step 3: Update to latest Anaconda.
You can check for updates in the command line:

conda update --prefix [path to anaconda] anaconda

## Step 4: Installing packages
Installing packages with Anaconda is easy. The basic format is:

conda install <list of packages>

For example, let's go ahead and install a few packages we'll need for this workshop.

conda install numpy scipy pandas matplotlib flask scikit-learn jupyter


## packages versions for my notebook: (*Note it's not reqired to install the exact versions)
==========================================================================
- matplotlib==3.1.3
- numpy==1.17.4
- pandas==0.25.3
- pandas-profiling==2.4.0
- scikit-learn==0.22.1
- scipy==1.3.2
- seaborn==0.9.0
