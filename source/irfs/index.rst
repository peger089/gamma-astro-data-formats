.. include:: ../references.txt

IACT IRFs
=========

The instrument response function (IRF) formats currently in use
for imaging atmospheric Cherenkov telescopes (IACTs) are stored in FITS
binary tables using the "multidimentional array" convention (binary tables with a
single row and array columns) described at :ref:`fits-arrays-bintable-hdu`.

This format has been used for calibration data and IRF of X-ray instruments,
as well as for the IRFs that are distributed with the Fermi-LAT science tools.

At the moment (November 2015), this format is used by H.E.S.S. and
VERITAS and supported by Gammapy and Gammalib and is being proposed for
DL3 IRFs (i.e. the format distributed to end users and used by the science tools
for CTA).
Note that a different format has been proposed for CTA to serialise multidimensional
arrays and axis information: http://adsabs.harvard.edu/abs/2015arXiv150807437W
As far as we know, this format is currently not supported by any analysis package.

Here we specify the IRFs in use for IACT data.

Specific IRFs
-------------

TODO: Copy over the format summary and descriptions from here:
https://gammapy.readthedocs.org/en/latest/dataformats/index.html#overview

Table of contents
-----------------

.. toctree::

   effective_area/index
   psf-ogip/index
   psf-gtpsf/index
   background/index
