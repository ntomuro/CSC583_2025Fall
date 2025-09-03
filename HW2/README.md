# CSC 583 HW#2 Setup Instructions

The base code is a notebook file, "hw2_word_vectors.ipynb".  Your task is to fill in the sections marked '# TODO' and answer questions marked "Write your answer here".  You must also write your name, course number etc. at the top of the file.

Supplemental image files, such as "question_2.1.png" and "question_2.1.png", are placed in the folder "imgs".

## ?? Setup

The code has been tested on Google Colab -- it runs as is with no additional setup.  You are encouraged to write code there.  

However, if you like to use your local platform, you are more than welcome to do so.
But make sure that it is at least Python version 3.8. If not, the easiest thing to do is to make sure you have at least 3GB free on your computer and then to head over to (https://www.anaconda.com/download/) and install the Python 3 version of Anaconda. It will work on any operating system.

After you have installed conda, close any open terminals you might have. Then open a new terminal and run the following command:

## 1. Create an environment with dependencies specified in env.yml:
    conda env create -f env.yml

## 2. Activate the new environment:
    conda activate 583hw2
    
## 3. Inside the new environment, install IPython kernel so we can use this environment in jupyter notebook: 
 
    python -m ipykernel install --user --name 583hw2

## 4. This homework is a Jupyter Notebook. With the above done you should be able to get underway by typing:

    jupyter notebook hw2_word_vectors.ipynb
    
## 5. To make sure we are using the right environment, go to the toolbar of hw2_word_vectors.ipynb, click on Kernel -> Change kernel, you should see and select 583hw2 in the drop-down menu.

## To deactivate an active environment, use
    conda deactivate
