# Learn SRAL

<hr>

[![Python](https://img.shields.io/badge/python%203.10-anaconda-green)](https://www.anaconda.com/products/distribution)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE.txt)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgitlab.eumetsat.int%2Feumetlab%2Foceans%2Focean-training%2Fsensors%2Flearn-sral/HEAD?urlpath=%2Ftree%2FIndex.ipynb)
[![WEkEO](https://img.shields.io/badge/launch-WEKEO-1a4696.svg?style=flat&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAA8AAAAMCAMAAACKnBfWAAAABGdBTUEAALGPC/xhBQAAACBjSFJNAAB6JgAAgIQAAPoAAACA6AAAdTAAAOpgAAA6mAAAF3CculE8AAABwlBMVEUAYbdepNtBc7VCdLhNhMQkXKpsn9RWltFZl9VlpNI3aK9fpNtMd7ZznM8pg8o4WJc2TZFHY6MmQYptiLxnqt5hptxfpNtfpNtfpNtgpdtip9x2uullqN1fpNtdo9pepdtanNQ9a65Bc7dCeb5nqt5fpNslUpssW6RMgcBTjstWldJhptxdo9phoNdkpdtfpNtoqNxepNplo9hepNthnNNfpdtelM1hptxSgL5dj8hoqt5fpNsjRYgjPog8WqBHa61TfLplqN1fpdtfpdxam9IyTIw2TZFGYaBoqt5hptxfpdtepNpfpNtgpdtjp9x5vu5do9pHgb5co9pepNtHgbwWN4AVP5AhU6JLgL9dl89epNphpttgpdtipttnqd1ho9glSIkWM3snSokeTJdHda9cksphndRmqNyTweaWxOePv+WfyemAs91QYphFUmpuclhKYHRwh5V8pNNdls6iyuq72fCNvuWIueCIlbtTW2hwcFNTY2lmfpSBpNJZj8lsq91xr99nqdx4suBrqds7V5AlNm85S20lRIJVcZxZgr1Uh8NcotpbotpdpNtGfrcTKnAOKXsYOYo4XKRJcbNHfbf////t/CgnAAAAUHRSTlMAAAAAAAAAAAAAAAAAAAAAAAAAAByF2PfyxGAJLcH+9pQvJgsav/7s57hBf/3gQdO69vH18dK4fN0+GLz96uSzPCq99JArIgkagNTz7r9bB4DtcFsAAAABYktHRJUIYHqDAAAAB3RJTUUH5wIKESIRAg6dCwAAALtJREFUCNdjYGAUERUTl5CUkmZiZmFlY2CUkZULAAJ5BUUlZXYOBhXVADAIVFPX0NTiZNDWAXKCgkNCw8IjInX1GPSjomNi4+ITEpOSU1LTDBgM0zMys7JzcvPyCwqLio0YjKNKSstKyisqq6prautMGEwD6hsam5pbWtvaOzq7zBjMdbq7g3p6+/onTJw02cKSwcoaYt8UG1s7ewcuBm5HJ7B7nF1c3dx5eBn4uD08vbx9fP38+QUEhYQB5Z40RP8+e1wAAAAldEVYdGRhdGU6Y3JlYXRlADIwMjMtMDItMTBUMTc6MzM6NDUrMDA6MDCCLR1xAAAAJXRFWHRkYXRlOm1vZGlmeQAyMDIzLTAyLTEwVDE3OjI2OjU5KzAwOjAw393bowAAAABJRU5ErkJggg==)](https://jupyterhub-wekeo.apps.eumetsat.dpi.wekeo.eu/hub/user-redirect/lab/tree/public/wekeo4oceans/learn-sral/Index.ipynb)

<hr>

The **learn-sral** module consists of a collection of python-based Jupyter-notebooks 
design to demonstrate the capability of the SAR Radar Altimeter (SRAL), carried 
by the Sentinel-3 satellites, and to help users begin to work with its data at 
level-1 and level-2. 

For any questions about this repository, please contact ops@eumetsat.int.

## License
 
This code is licensed under an MIT license. See file LICENSE.txt for details on 
the usage and distribution terms. No dependencies are distributed as part of this 
package. Copyright EUMETSAT 2024.

All product names, logos, and brands are property of their respective owners. 
All company, product and service names used in this website are for identification 
purposes only.

## Authors

* [**Ben Loveday**](mailto://ops@eumetsat.int) - [EUMETSAT](http://www.eumetsat.int)
* [**Hayley Evers-King**](mailto://ops@eumetsat.int) - [EUMETSAT](http://www.eumetsat.int)

Please see the AUTHORS.txt file for more information on contributors.

## Prerequisites

You will require `Jupyter Notebook` to run this code. We recommend that you install 
the latest [Anaconda Python distribution](https://www.anaconda.com/) for your 
operating system. Anaconda Python distributions include Jupyter Notebook.

## Dependencies

|item|version|licence|package info|
|---|---|---|---|
|bokeh|3.2.1|BSD-3|https://anaconda.org/conda-forge/bokeh|
|cartopy|0.23.0|LGPL-3|https://scitools.org.uk/cartopy/docs/latest/copyright.html|
|cmocean|4.0.3|MIT|https://anaconda.org/conda-forge/cmocean|
|dask|2024.6.0|BSD-3|https://anaconda.org/conda-forge/dask|
|distributed|2024.6.0|BSD-3|https://anaconda.org/conda-forge/distributed/| 
|hda|2.16|Apache-2.0|https://pypi.org/project/hda|
|ipywidgets|8.1.3|BSD-3|https://anaconda.org/conda-forge/ipywidgets|
|jupyterlab|4.2.2|BSD-3|https://anaconda.org/conda-forge/jupyterlab|
|matplotlib|3.8.4|PSFL|https://matplotlib.org/stable/users/project/license.html|
|netcdf4|1.7.1|MIT|https://anaconda.org/conda-forge/netcdf4|
|python|3.10.14|PSF|https://docs.python.org/3/license.html|
|scipy|1.13.0|BSD-3|https://anaconda.org/conda-forge/scipy|
|xarray|2024.6.0|Apache-2.0|https://anaconda.org/conda-forge/xarray|
|eumartools|0.0.1|MIT|https://anaconda.org/cmts/eumartools|
|eumdac|2.2.2|MIT|https://anaconda.org/eumetsat/eumdac|
|scikit-image|0.22.0|BSD-3|https://anaconda.org/conda-forge/scikit-image|
|shapely|2.0.3|BSD-3|https://anaconda.org/conda-forge/shapely|

## Installation

The simplest and best way to install these packages is via Git. Users can clone this 
repository by running the following commands from either their [terminal](https://tinyurl.com/2s44595a) 
(on Linux/OSx), or from the [Anaconda prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/). 

You can usually find your terminal in the start menu of most Linux distributions 
and in the Applications/Utilities folder  on OSx. Alternatively, you should be 
able to find/open your Anaconda prompt from your start menu (or dock, or via running 
the Anaconda Navigator). Once you have opened a terminal/prompt, you should navigate 
to the directory where you want to put the code. Once you are in the correct directory, 
you should run the following command;

`git clone --recurse-submodules --remote-submodules https://gitlab.eumetsat.int/eumetlab/oceans/ocean-training/sensors/learn-sral.git`

*Note: if you are using an older version of git, you may find that your submodules are empty. In this case, you need to remove the folder and re-run the line above with `--recursive` added to the end*

This will make a local copy of all the relevant files.

*Note: If you find that you are missing packages, you should check that you ran 
`git clone` with both the `--recurse-submodules` and `--remote-submodules` options.*

*Note: if you are using an older version of git, you may find that your submodules are empty. In this case, you need to remove the folder and re-run the line above with `--recursive` added to the end*

## Usage

This collection supports Python 3.10. Although many options are possible, the 
authors highly recommend that users install the appropriate Anaconda package 
for their operating system. In order to ensure that you have all the required 
dependencies, we recommend that you build a suitable Python environment, as 
discussed below.

### Python environments

Python allows users to create specific environments that suit their applications. 
This tutorials included in this collection require a number of non-standard 
packages - e.g. those that are not included by default in Anaconda. In this 
directory, users will find a *environment.yaml* file which can be used to 
construct an environment that will install all the required packages.

To construct the environment, you should open either **terminal** (Linux/OSx) 
or an **Anaconda prompt** window and navigate to repository folder you downloaded 
in the **Installation** section above. In this folder there is a file called 
**environment.yml**. This contains all the information we need to install the relevant 
packages.

The conda package manager can be very slow, so we will install a new "solver" that 
speeds things up. To do this, from the Anaconda prompt (Windows) or in the terminal (OSx/Linux) 
you can run:

`conda install -n base conda-libmamba-solver`

Once the line above is run, to create out Python environment, we run:

`conda env create -f environment.yml --solver=libmamba`

This will create a Python environment called **cmts_learn_sral**. The environment 
won't be activated by default. To activate it, run:

`conda activate cmts_learn_sral`

Now you are ready to go!

*Note: remember that you may need to reactivate the environment in every 
new window instance*

*Note: if you get a warning that "solver" is not a valid conda argument, you can 
skip the libmamba install and run:* `conda env create -f environment.yml`

### Running Jupyter Notebook

This module is based around a series of [Jupyter Notebooks](https://jupyter.org/). These support high-level interactive learning by allowing us to combine code, text description and data visualisations. If you have not worked with `Jupyter Notebooks` 
before, please look at the [Introduction to Python and Project Jupyter](./working-with-python/Intro_to_Python_and_Jupyter.ipynb) module to get a short introduction to their usage and benefits.

To run Jupyter Notebook, open a terminal or Anaconda prompt and make sure you have activated 
the correct environment. Again, navigate to the repository folder. Now you can run Jupyter using:

`jupyter lab` or `jupyter-lab`, depending on your operating system.

This should open Jupyter Notebooks in a browser window. On occasion, Jupyter may not
be able to open a window and will give you a URL to past in your browser. Please do
so, if required.

*Note: Jupyter Notebook is not able to find modules that are 'above' it in a directory 
tree, and you will unable to navigate to these. So make sure you run the line above 
from the correct directory!*

Now you can run the notebooks! We recommend you start with the [Index](./Index.ipynb) module.

### Collaborating, contributing and issues

If you would like to collaborate on a part of this code base or contribute to it 
please contact us on training@eumetsat.int. If you are have issues and 
need help, or you have found something that doesn't work, then please contact us 
at ops@eumetsat.int. We welcome your feedback!

<hr>
<hr>