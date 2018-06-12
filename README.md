## PyCon Israel Keynote

Slides and notebooks from PyCon Israel 2018 KeyNote.

### View Online

The core of this talk is a series of notebooks. These can be viewed here:

* [Cookie count](https://nbviewer.jupyter.org/github/birdsarah/pyconil18/blob/master/notebooks/A%20look%20at%20my%20cookies......ipynb)
* [Cookie syncing](https://nbviewer.jupyter.org/github/birdsarah/pyconil18/blob/master/notebooks/A%20look%20at%20my%20cookies......syncing.ipynb)
* [Zombie cookies - 1](https://nbviewer.jupyter.org/github/birdsarah/pyconil18/blob/master/notebooks/A%20look%20at%20my%20local%20storage......ipynb)
* [Zombie cookies - 2](https://htmlpreview.github.io/?https://github.com/birdsarah/pyconil18/blob/master/notebooks/A%20look%20at%20my%20cookies.....evercookie%20test.html)
* [Overscripted analysis](https://nbviewer.jupyter.org/github/birdsarah/pyconil18/blob/master/notebooks/overscripted-canvas-fingerprinting.ipynb)
* [Slides](https://github.com/birdsarah/pyconil18/blob/master/slides.md)


### Run locally

1) Install [Anaconda](https://www.anaconda.com/download) or [Miniconda](https://conda.io/miniconda.html)

2) Setup and activate environment

    $ conda env create -f environment.yaml
    $ conda activate pyconil18

3) Run Jupyter

    $ cd notebooks
    $ jupyter notebook

Notes:

 * You will need to specify your own firefox profile directory.
 * Only one of the analyses mentioned for the
   [OverScripted](https://github.com/mozilla/Overscripted-Data-Analysis-Challenge)
   data set is given.  You are encouraged to download and play with the
   [OverScripted](https://github.com/mozilla/Overscripted-Data-Analysis-Challenge)
   dataset and enter the analysis challenge.

Sources:

 * `disconnect_me.json` provided was downloaded from
   https://github.com/disconnectme/disconnect-tracking-protection/blob/master/services.json
