# Project description
Generate student score data for quiz and assignments for testing various data visualization techniques. The data is generated using beta distribution, with one assumption(s) that the scores are between 0 - 100 and the avearge time spent on each quiz(and time of submisstion) by a student is random(as sampled from a normal distribution).   

# Installation Requirements
I highly recommend anaconda virtual environment for this, or any python project, since anaconda automatically configures the correct(conflict free) version numbers for python libraries. check the required imports in environment.yml file. 

# how to run
follow the steps to run the project: 

1. Install anaconda (https://docs.anaconda.com/anaconda/install/)
2. open anaconda terminal if you are using Windows (for MacOS & other Linux based distros use the terminal)
3. Install git by running the following command from the anaconda terminal 'conda install -c anaconda git'
4. clone this repository by entering 'git clone https://github.com/hamzamk/Sample_ClassData_generator/'
5. cd into the cloned directory(if you haven't)
6. run the following command 'conda env create -f environment.yml' (https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
7. activate the 'datavis' environment by running the following command 'conda activate datavis'
8. run jupyter notebook by entering the following commdand 'jupyter notebook'
9. locate the .ipynb file in the new browser tab which opened automatically and run the notebook


