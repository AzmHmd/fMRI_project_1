…or create a new repository on the command line

echo "# fMRI_project_1" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/AzmHmd/fMRI_project_1.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/AzmHmd/fMRI_project_1.git
git push -u origin master

----------------------------------------------------------------------------------------
In order to use the GUI, type:
Ssh username@sunbird.swansea.ac.uk

In order to code in python:
Module load python/3.7.0
Module load Anaconda/3
Module load CUDA/8.0


Conda create --name project_1
Source activate project_1

List all discoverable environments:
Conda info --envs

Get the required libraries:
pip install tensorflow-gpu
Pip install keras

Python 
Import keras
Import tensorflow

