
IPython for interactive data analysis
================

* Date 02-12-2014 
* CNRCWP modelling and data analysis workshop, Montreal
* Link to this document: http://tinyurl.com/cnrcwp-ipython-workshop


Preparation
-----------
 * If you do not have an account on skynet3, please let me know
 * After you have logged in to skynet3, source a profile
  
  ```bash
    . ~huziy/.profile_usr
  ``` 




Plan
-----------

* Familiarize with IPython
  
    * Create and save notebooks, running a cell
    * `%%bash` - magic
    * TAB - autocomplete, Shift+TAB - help on function parameters
    
* Python
    
    * How to define a function, write a loop, use modules

* Matplotlib (basics)
    
    * Create and plot a matrix using pcolormesh and contourf

    * Show an example of 3D map from here -- https://basemaptutorial.readthedocs.org/en/latest/basemap3d.html#adding-3d-bars

* Interactive (simple)
    
    * plot y = x * sin(k*x) with widgets


* Interactive (harder)

    * Data for the workshop is in the folder: /home/huziy/skynet3_rech1/dfs_data_for_cnrcwp_tutorial_3dec_2014
    * Create a setup where:
        
        * A variable can be selected
        * Colormap can be selected
        * Color levels

* Show how to calculate seasonal mean fields
* Plot wind vectors
    

Modules used during the tutorial
--------------------------------
 
* numpy - for manipulating arrays
* matplotlib - for plotting graphs (needed by basemap) 
* basemap - for plotting on maps 
* netCDF4 - for reading netcdf files
* pandas - for calculation of seasonal means
* os  - standard python module (installed with python)

Usually I install the modules using `pip` as follows:

```bash
    pip install numpy
```

To list installed modules do:

```bash
    pip list
```

Notebooks which were created during the tutorial
-----------

0. [A trivial example of using control widgets in IPython notebooks](http://nbviewer.ipython.org/github/guziy/PyNotebooks/blob/master/nb_tutorial/slider_trivial.ipynb)
1.  [Plotting a 2d global field with parameterized widgets](http://nbviewer.ipython.org/github/guziy/PyNotebooks/blob/master/nb_tutorial/dfs_data_explore.ipynb)
2. [Seasonal mean and wind plot](http://nbviewer.ipython.org/github/guziy/PyNotebooks/blob/master/nb_tutorial/seasonal_mean_and_wind_plot.ipynb)
3. Note that you'll need to download the notebooks and open them in an ipython notebook application in order to see the interactive widgets, which allow to change plot parameters on the fly



References
-----------
* If you need to download and install python -- https://www.python.org/
* IPython documentation and tutorials -- http://ipython.org/
* Python tutorial given at CMOS2014 -- http://tinyurl.com/cmos2014
* Examples of IPython notebooks -- http://nbviewer.ipython.org/
* To read on scientific stack in Python -- http://www.scipy.org/
* Matplotlib gallery -- http://matplotlib.org/gallery.html
* Basemap tutorial (for plotting geographical data on maps) -- https://basemaptutorial.readthedocs.org/en/latest/
* Python for MATLAB users -- http://nbviewer.ipython.org/github/gestaltrevision/python_for_visres/blob/master/Part3/Part3_Scientific_Python.ipynb 









