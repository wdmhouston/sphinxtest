.. ProjectName documentation master file, created by
   sphinx-quickstart on Sun Sep 19 19:50:13 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Fruit Recognition Web Api's documentation!
==========================================================================================================

#####################################################
Tutorial 1: First Steps
#####################################################

**Context**

In this tutorial, we use a single-phase flow solver 
to solve for pressure propagation on a 10x10x10 cube mesh
with anisotropic permeability values.
The pressure source is the lowest-left corner element, and the pressure sink sits at the opposite top corner.


At the end of this tutorial you will know:

  - the basic structure of XML input files used by GEOSX,
  - how to run GEOSX on a simple case requiring no external input files,
  - the basic syntax of a solver block for single-phase problems,
  - how to control output and visualize results.

**Input file**

GEOSX runs by reading user input information from one or more XML files.
For this tutorial, we only need a single GEOSX input file located at:

**Running GEOSX**

If our XML input file is called ``my_input.xml``, GEOSX runs this file by executing:

.. code-block:: console

  /path/to/geosx -i /path/to/my_input.xml

The ``-i`` flag indicates the path to the XML input file.
To get help on what other command line input flags GEOSX supports, run ``geosx --help``.


.. toctree::
   :maxdepth: 2
   :caption: Contents:


Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
