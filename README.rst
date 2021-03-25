SatMAD Applications and Examples
=============================================

|Documentation Status|

SatMAD is an open source Python package, aiming at providing the base functionality to solve
satellite mission analysis and design as well as orbital mechanics problems with enough precision and performance
to be used in the design and operation of real satellites.

This project contains applications, analyses and examples with SatMAD project.


Documentation
--------------------------

The documentation for SatMAD is here: https://satmad.readthedocs.io/

The documentation of SatMAD-Applications with all the analyses and examples are here: https://satmad-applications.readthedocs.io

The documentation contains text-only version of these analyses. For more hands-on Jupyter notebooks, you can try
github address of the
`satmad-applications project <https://github.com/egemenimre/satmad_applications/tree/main/docs/analyses>`_.

Installing SatMAD
-----------------

The SatMAD package is on `PyPI`_ and you can install it simply by running::

    pip install satmad

You can also install it via `conda-forge`_::

    conda install -c conda-forge satmad

Do not install `satmad` using `sudo`.

You can find the source code on GitHub: https://github.com/egemenimre/satmad

.. _`PyPI`: https://pypi.org/project/satmad/
.. _`conda-forge`: https://github.com/conda-forge/satmad-feedstock

Requirements
------------

-   SatMAD provides most of the orbital mechanics routines for the analyses
-   NumPy and SciPy are used for the underlying mathematical algorithms
-   Matplotlib is used for plots
-   Astropy handles all time and reference frame computations


License
-------

This project is Copyright (c) Egemen Imre and licensed under
the terms of the GNU GPL v3+ license.

.. |Documentation Status| image:: https://readthedocs.org/projects/satmad-applications/badge/?version=latest
    :target: https://satmad-applications.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status
