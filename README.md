## Artificial Intelligence & Adaptive Systems

This is a repository for the Artificial Intelligence and Adaptive Systems
class (CITS4404) offered at the University of Western Australia
taught by Dr. Yuliya Karpievitch

Below is a short introduction on how to intall/use Python for the AI class.
Please go through these steps to assure you have a working Jupyter Notebook.


### Installation instructions

To prepare for this tutorial, you have these options:

1) Install Jupyter on your laptop and download my code from Git.

2) Run the Jupyter notebook on Google Colab.
This is the easiest option, with one drawback: the virtual machine you get is temporary and requires internte connection. You can save yout files on Google Drive.


Option 1 is the best choice if you are able to do it ahead of time, because it does not depend on the network.  Option 2 depends on network performance, which is unpredictable.  



### Option 1

If you don't already have Jupyter, I recommend installing Anaconda or Miniconda (I use miniconda), which allows user-level package installation and thus will not interfere with other Python installations or environments.
It works on Windows, Mac and Linux.

[Information about installing Anaconda is here](http://docs.continuum.io/anaconda/install.html).

The code for the tutorial works in Python 3.

With the installation of Anaconda, you should get Jupyter by default, if not, run

```
    conda install jupyter
```

Once you have Jupyter, you can get my code from  the Git repository on GitHub.  If you have a Git client installed, you should be able to clone also, but be aware that I will be uopdating the files as we progress, so you will have to merge your updated files.  

To clone the repo:

```
    git clone https://github.com/AllenDowney/ThinkComplexity2.git
```

Tha should create a directory called `AIclass`.
Otherwise you can download the repository in [this zip file](https://github.com/AllenDowney/ThinkComplexity2/archive/master.zip)
and unzip it.

Then "cd" into the new directory:

```
    cd AIclass
```

To make sure you have the packages you need, you can use "environment.yml"
to create a Conda environment named `AIclass`

```
   conda env create -f environment.yml
```

Then activate the new environment

 ```
   conda activate AIclass
```

To start Jupyter, run:

```
    cd code
    jupyter notebook
```

Jupyter will launch your default browser or open a tab in an existing browser window.
Othrwise, Jupyter server will print a URL you can paste into the browser URL line.  For example, when I launch Jupyter, I get

```
jupyter notebook
[I 23:14:52.336 NotebookApp] Serving notebooks from local directory: /Users/yuliya/AI/2019/code
[I 23:14:52.336 NotebookApp] The Jupyter Notebook is running at:
[I 23:14:52.336 NotebookApp] http://localhost:8890/?token=f651b68132dab6931334db61a27ea155007ad6323634a253
[I 23:14:52.337 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).
[C 23:14:52.355 NotebookApp] 
    
    To access the notebook, open this file in a browser:
        file:///Users/yuliya/Library/Jupyter/runtime/nbserver-56529-open.html
    Or copy and paste one of these URLs:
        http://localhost:8890/?token=f651b68132dab6931334db61a27ea155007ad6323634a253

```
 
When you start your server, you may get a different URL.
Whatever it is, if you paste it into a browser, you should see a list of notebooks in the repository.

Click on "L1_Python_intro.ipynb".  It should open that notebook.

Select the cell with the import statements and click "Run" or press "Shift-Enter" to run the code in that cell.
If it works and you get no error messages, **you are ready to rock-and-roll!**.  

If you get error messages about missing packages, you can install those packages using your conda.



### Option 2

You can run the class notebooks in Google Colab by uploading the Notebook to Colab. 

You should see a home page with a list of the notebooks in the repository.

Open "L1_Python_intro.ipynb". You should be able to run the notebook in your browser 
and try out the examples.  

However, be aware that the virtual machine you are running is temporary.
If you leave it idle for, it will disconnect.

