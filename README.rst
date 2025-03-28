PynPoint
========

**Pipeline for processing and analysis of high-contrast imaging data**

.. container::

    |PyPI Status| |Python Versions| |CI Status| |Docs Status| |Code Coverage| |Code Quality| |License|

PynPoint is a generic, end-to-end pipeline for the reduction and analysis of high-contrast imaging data of exoplanets. The pipeline uses principal component analysis (PCA) for the subtraction of the stellar PSF and supports post-processing with ADI, RDI, and SDI techniques. The package is stable, extensively tested, and actively maintained.

Documentation
-------------

Documentation is available at `http://pynpoint.readthedocs.io <http://pynpoint.readthedocs.io>`_, including installation instructions, details on the pipeline architecture, and several notebook tutorials.

Attribution
-----------

If you use PynPoint in your publication then please cite `Stolker et al. (2019) <https://ui.adsabs.harvard.edu/abs/2019A%26A...621A..59S/abstract>`_. Please also cite `Amara & Quanz (2012) <https://ui.adsabs.harvard.edu/abs/2012MNRAS.427..948A/abstract>`_ as the origin of PynPoint, which focused initially on the use of PCA as a PSF subtraction method. In case you use specifically the PCA-based background subtraction module or the wavelet based speckle suppression module, please give credit to `Hunziker et al. (2018) <https://ui.adsabs.harvard.edu/abs/2018A%26A...611A..23H/abstract>`_ or `Bonse et al. (preprint) <https://ui.adsabs.harvard.edu/abs/2018arXiv180405063B/abstract>`_, respectively.

Contributing
------------

Contributions in the form of bug fixes, new or improved functionalities, and pipeline modules are highly appreciated. Please consider forking the repository and creating a pull request to help improve and extend the package. Instructions for `coding of a pipeline module <https://pynpoint.readthedocs.io/en/latest/coding.html>`_ are available in the documentation. Bugs can be reported by creating an `issue <https://github.com/PynPoint/PynPoint/issues>`_ on the Github page.

License
-------

Copyright 2014-2021 Tomas Stolker, Markus Bonse, Sascha Quanz, Adam Amara, and `contributors <https://github.com/PynPoint/PynPoint/graphs/contributors>`_.

PynPoint is distributed under the GNU General Public License v3. See the `LICENSE <https://github.com/PynPoint/PynPoint/blob/main/LICENSE>`_ file for the terms and conditions.

Acknowledgements
----------------

The PynPoint logo was designed by `Atlas Digital <https://atlas-digital.nl>`_ and is `available <https://quanz-group.ethz.ch/research/algorithms/pynpoint.html>`_ for use in presentations.

.. |PyPI Status| image:: https://img.shields.io/pypi/v/pynpoint
   :target: https://pypi.python.org/pypi/pynpoint

.. |Python Versions| image:: https://img.shields.io/pypi/pyversions/pynpoint
   :target: https://pypi.python.org/pypi/pynpoint

.. |CI Status| image:: https://github.com/PynPoint/PynPoint/actions/workflows/main.yml/badge.svg
   :target: https://github.com/PynPoint/PynPoint/actions

.. |Docs Status| image:: https://img.shields.io/readthedocs/pynpoint
   :target: http://pynpoint.readthedocs.io

.. |Code Coverage| image:: https://codecov.io/gh/PynPoint/PynPoint/branch/main/graph/badge.svg?token=LSSCPMJ5JH
   :target: https://codecov.io/gh/PynPoint/PynPoint

.. |Code Quality| image:: https://img.shields.io/codefactor/grade/github/PynPoint/PynPoint
   :target: https://www.codefactor.io/repository/github/PynPoint/PynPoint

.. |License| image:: https://img.shields.io/github/license/PynPoint/PynPoint
   :target: https://github.com/PynPoint/PynPoint/blob/main/LICENSE
