The purpose of this GitHub repository is to host the required files to run a Jupyter notebook.

## My personal reasons to choose this project
My main research as a PhD student at the University of Lund, Sweden focuses in analysing data recorded by the ALICE experiment at CERN. From distributions constructed with real data, I apply statistical methods to study the phenomena happening in proton-proton and heavy-ion collisions and try to connect observations with the underlying physics mechanisms.
However I am also interested in applying my skills as an experimental physicist to study phenomena outside of academia, such as, the evolution of COVID-19 pandemic or to the industrial and finantial sectors. Having said that the purpose of the Jupyter notebook is to analyse the data provided by the Johns Hopkins Center for Systems Science and Engineering of the Novel Coronavirus (COVID-19) [JHUCSSE](https://github.com/CSSEGISandData) Cases in the United States.


## What you will find in this GitHub repository

In this respostory you will find the file, environment.yml, which sets the enviroment needed to run a Jupyter notebook 

## Instructions for running the notebook

1. Install [miniconda3](https://docs.conda.io/en/latest/miniconda.html).

2. Download the files from this repository and unzip

3. In the terminal, navigate to the folder you downloaded from GitHub

4. Install the ``` LUcompute ``` environment by running the follwing lines  
	
  ```
  conda env create -f environment.yml
  conda activate LUcompute	  
  ```
5. Run the notebook by typing
```
jupyter notebook
```
