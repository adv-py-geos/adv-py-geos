## How to submit homework 1

Create a notebook that reads in your dataset. 

Submit this notebook in a new directory. Include an environment.yml if needed. Here is a basic file called `pong.yml`:

    name: pong
    channels:
      - conda-forge
      - defaults
    dependencies:
      - conda
      - python=3.7
      - scipy
      - shapely
      - cmocean
      - cartopy
      - jupyterhub
      - dask
      - netcdf4
      - pandas
      - jupyter
      - jupyterlab
      - nodejs
      - xgcm
      - ipython
      - numpy
      - seaborn
      - fiona
      - matplotlib
      - xarray
      - holoviews
      - geoviews
      - xrviz
      - xhistogram
      - gsw
      - ffmpeg
      - hvplot
      - nc-time-axis
      - jupyter_contrib_nbextensions
      - zarr
    prefix: /Users/rob/miniconda3
