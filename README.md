ipyaladin
===============================

Description
-----------

A bridge between Jupyter and Aladin Lite, enabling interactive sky visualization in IPython notebooks.

Installation
------------

To install use pip:

    $ pip install ipyaladin
    $ jupyter nbextension enable --py --sys-prefix ipyaladin


For a development installation (requires npm) you can either do:

    $ git clone https://github.com/cds-astro/ipyaladin
    $ cd ipyaladin
    $ pip install -e .
    $ jupyter nbextension install --py --symlink --sys-prefix ipyaladin
    $ jupyter nbextension enable --py --sys-prefix ipyaladin

or directly use the compile.sh script:

    $ git clone https://github.com/cds-astro/ipyaladin
    $ cd ipyaladin
    $ ./compile.sh

Note:
Sometimes the module installation crash because of a conflict with an older occurence of itself, if so to solve this problem go to:  ~/anaconda3/share/jupyter/nbextensions
Then suppress the jupyter-widget-ipyaladin corrupted file.