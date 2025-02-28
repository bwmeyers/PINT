.. _`Tutorials`:

Tutorials
=========

These are step-by-step guides you can follow to show you what PINT can do. If you want some explanations of why things work this way, see the :ref:`Explanation` section. If you want details on a particular function that comes up, see the :ref:`Reference` section. If you have a particular thing you want instructions on doing, see the :ref:`How-tos`.

Data Files
----------

The data files (``par`` and ``tim``) associated with the tutorials and
other examples can be located via :func:`pint.config.examplefile`
(available via the :mod:`pint.config` module):

::

   import pint.config
   fullfilename = pint.config.examplefile(filename)


For example, the file ``NGC6440E.par`` from the
`Time a Pulsar`_ notebook can be found via:

::

   import pint
   fullfilename = pint.config.examplefile("NGC6440E.par")

Examples
--------
   
We don't really have any proper tutorials yet. But for the moment, we
have a few examples that may be useful.  These tutorials examples are in the form of Jupyter notebooks, downloadable from a link at the top of each page. (Also available in the same place is a plain-python script version, in case this is more convenient.) You should be able to download these files and run them from anywhere convenient (provided ``PINT`` is installed). 

.. toctree::

   basic-installation
   examples/time_a_pulsar.ipynb
   examples/PINT_walkthrough.ipynb
   examples/fit_NGC6440E.ipynb
   examples/understanding_timing_models.ipynb
   examples/understanding_parameters.ipynb
   examples/build_model_from_scratch.ipynb
   examples/How_to_build_a_timing_model_component.ipynb
   examples/understanding_fitters.ipynb
   examples/Wideband_TOA_walkthrough.ipynb
   examples/Simulate_and_make_MassMass.ipynb
   examples-rendered/paper_validation_example.ipynb


.. _`Time a Pulsar`: examples/time_a_pulsar.html
