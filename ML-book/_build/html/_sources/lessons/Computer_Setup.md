# Setting up your computer

Since one goal of this course is to equip you with the skills to do original research in machine learning using the
best-in-class tools, we want to start out using the most commonly used tools and environments in the industry. Without a doubt
Linux and Mac (because of its near perfect compatibility with Linux) are the preferred operating systems for
machine learning research. If you have a linux or Mac machine, setup will we very easy. If you have windows, you'll want to
install WSL (Windows Subsystem for Linux) to give you a linux layer running close to native hardware.

## Macintosh Install

1. Install `miniconda` to manage your python environments using [instructions here](https://docs.anaconda.com/miniconda/#quick-command-line-install)
2. Create an environment with `conda create -n ML_Class python-3.11.10`
3. activate the envirnoment `conda activate ML_Class`
4. create a directory for your work: `mkdir ML_Class` and `cd ML_Class`
5. Copy [this file](../requirements.txt) to your folder `~/ml` as `requirements.txt`.
6. Install the libraries `pip install -r requirements.txt`
7. Everything should install with no errors (warnings are OK.)
8. See if jupyter is working: `jupyter-lab` (should open a browser)

## Linux Install

Follow the Mac instructions

## Windows Install (WSL)

1. Install WSL2 if you haven't already (Windows Subsystem for Linux) following [these instructions](https://learn.microsoft.com/en-us/windows/wsl/install). Be sure to select Ubuntu 22 for your distribution (unless you are sure you will never need to ask me for help).
2. Enter the WSL shell and then follow the Mac instructions
3. WSL Problems: [Fix posted!](../lessons/wsl.md)

### Anaconda Option (last resort)

If the WSL route is too complicated for now or just not working, Anaconda will get you up
and running. The reason this is not recommended is that Anaconda installs a LOT of software and does a LOT of setup behind the scenes. And when you want to change something, or bypass Anaconda for a reason, it can be tricky to disable it. That said, it is very popular and good at what it does.

Install [Anaconda for Windows](https://anaconda.cloud/api/iam/email/verified/1a8a9aa0-e28f-4ceb-9ca4-b29dde699d5c)
