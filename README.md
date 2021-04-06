## My personal reasons to choose this project
My research as a PhD student at the University of Lund, Sweden focuses in analysing data recorded by the ALICE experiment at CERN. From distributions constructed with real data, I apply statistical methods to study the phenomena from proton-proton and heavy-ion collisions and try to connect our observations with the underlying physics mechanisms.
However I am also interested in applying my skills as an experimental physicist to investigate phenomena outside of academia, such as, the evolution of coronavirus disease 2019 (COVID-19) pandemic or to the industrial and finantial sectors. Having said that the purpose of the Jupyter notebook is to study the number of cases of COVID-19 in the USA. The data is hosted by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University, Baltimore, MD, USA and can be found in the [GitHub repository](https://github.com/CSSEGISandData). In addition an online interactive dashboard, hosted by CSSE has been developed to visualise and track reported cases of COVID-19 in real time. More details can be found in [DOI:](https://doi.org/10.1016/S1473-3099(20)30120-1)

## What you will find in this GitHub repository

The purpose of this GitHub repository is to host the required files to run a Jupyter notebook. You will find the file ``` environment.yml ```, which sets the enviroment needed to run the Jupyter notebook 

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
