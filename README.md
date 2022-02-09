# 001_NextEclipse

GIS project 001: Program to create a map of exlipse and cities of your input country

To see how it looks like clikc this [link](https://nbviewer.org/github/asamirice/001_NextEclipse/blob/main/Notebook/WhenIsYourNextEclipse.ipynb)

Since this is my first GIS coding project, I referenced Christy's [PlanYourNextEclipseViewing](https://github.com/christyheaton/PlanYourNextEclipseViewing) project.


## Data Source
* [Eclipse Data](http://xjubier.free.fr/en/site_pages/SolarEclipsesGoogleEarth.html)
* [City Data](http://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-populated-places/)

## Getting Started
* Install Miniconda for your operating system. Please choose the latest Python 3.x version. The installation instructions might be helpful.
* You should now have access to an Anaconda command prompt, open it like you would any program. Note that you should see ```(base)``` somewhere in your prompt. This means you're in the base Conda environment, which we will now change.

1. Navigate to the directory containing environment.yml (included in the repo).
```python
cd [location where you saved the repo]/PlanYourNextEclipseViewing
```

2. Create the Conda environment you will need to run the tutorial. Note: it is called geopandasenv. This could take anywhere from 10-30 minutes to finish.
```python
conda env create environment.yml
```

3. Now you can activate the environment.
```python
source activate geopandasenv  # macOS and Linux
activate geopandasenv  # Windows.
```

5. To open the Jupyter Notebooks, in your Anaconda prompt navigated to the Notebook directory, type in:
```python
jupyter notebook
```

6. If you ever want to deactivate the geopandasenv environment, type the following in your Anaconda prompt:
```python
source deactivate  # macOS and Linux
deactivate  # Windows.
```

That is all for now. Hope you enjoy this.
