# CSDMS 2016

Notebooks for the CSDMS annual meeting May, 2016

## Python Data Tools

There are many recent additions to Python that make it an excellent programming language for data analysis. This tutorial has two goals: 

1. First, we discuss several of the recent Python modules for data analysis in the form of notebooks that provide hands-on exercises for manipulating and analyzing data using pandas, scikit-learn, cytoolz, dask, and several new visualization libraries. 
2. Second, we execute examples using the Jupyter notebook, a web-based interactive development environment that facilitates documentation, sharing, and remote execution. 

Together these tools create a powerful, new way to approach scientific workflows for data analysis.


### Setup

I would install the latest python package from [Anaconda](https://www.continuum.io/downloads).  This should have everything you need to run the notebook examples.  You can even consider using [miniconda](http://conda.pydata.org/miniconda.html).

Here are the commands you will need to execute to install the packages for this session:

    conda install jupyter
    conda install matplotlib
    conda install pandas
    conda install scikit-learn
    conda install cytoolz
    
For the **Dask** example, you'll also need:

    conda install dask
    conda install h5py
    conda install pil
    
    pip install graphviz

If you'd like to play with some of the visualization libraries, please also install these:

    conda install seaborn
    conda install bokeh
    conda install mpld3

    pip install plotly
    pip install cufflinks
    pip install ggplot
    
