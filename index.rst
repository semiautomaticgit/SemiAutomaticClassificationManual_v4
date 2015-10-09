.. Semi-Automatic Classification Plugin documentation master file

Semi-Automatic Classification Plugin's User Manual
================================================================

.. |br| raw:: html

  <br />

Written by `Luca Congedo <http://www.researchgate.net/profile/Luca_Congedo>`_, the **Semi-Automatic Classification Plugin** (SCP) is a free open source plugin for `QGIS <http://www.qgis.org>`_ that allows for the **semi-automatic classification** (also supervised classification) of remote sensing images. Also, it provides several tools for the pre processing of images, the post processing of classifications, and the raster calculation.

SCP allows for the rapid creation of **ROIs** (training areas), through **region growing** algorithm, which are stored in a shapefile. The **scatter plot** or ROIs is available.
Spectral signatures of training areas are calculated automatically, and can be displayed in a **spectral signature plot** along with the values thereof. Spectral distances among signatures (e.g. Jeffries Matusita distance, or spectral angle) can be calculated for assessing **spectral separability**.
Spectral signatures can be exported and imported from external sources. Also, a tool allows for the selection and **download of spectral signatures** from the `USGS Spectral Library <http://speclab.cr.usgs.gov/spectral-lib.html>`_ .

SCP implements a tool for **searching and downloading Landsat and Sentinel** images.
The following tools are available for the **pre processing** of images: **automatic Landsat conversion to surface reflectance**, **clipping** multiple rasters, and **splitting** multi-band rasters.

The **classification algorithms** available are: Minimum Distance, Maximum Likelihood, Spectral Angle Mapping. SCP allows for interactive **preview of classification**.

The **post processing** tools include: **accuracy assessment**, land cover change, classification report, classification to vector, reclassification of raster values.
Also, a band calc tool allows for the **raster calculation** using `NumPy functions <http://docs.scipy.org/doc/numpy/reference/routines.math.html>`_ .

For more information and tutorials visit the official site `From GIS to Remote Sensing <http://fromgistors.blogspot.com/>`_.

|br| 

**How to cite:**

*Congedo Luca, Munafo' Michele, Macchi Silvia (2013). "Investigating the Relationship between Land Cover and Vulnerability to Climate Change in Dar es Salaam". Working Paper, Rome: Sapienza University.* Available at:
http://www.planning4adaptation.eu/Docs/papers/08_NWP-DoM_for_LCC_in_Dar_using_Landsat_Imagery.pdf

|br|

**License:**

Except where otherwise noted, content of this work is licensed under a `Creative Commons
Attribution-ShareAlike 4.0 International License <http://creativecommons.org/licenses/by-sa/4.0/>`_.

|br|

``Semi-Automatic Classification Plugin is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, version 3 of the License.
Semi-Automatic Classification Plugin is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
See the GNU General Public License for more details. You should have received a copy of the GNU General Public License along with Semi-Automatic Classification Plugin. If not, see http://www.gnu.org/licenses/.``


``The first version of the Semi-Automatic Classification Plugin was written by Luca Congedo for the Adapting to Climate Change in Coastal Dar es Salaam Project (http://www.planning4adaptation.eu).``

|br|

.. toctree::
	:maxdepth: 2
	:numbered:
  
	Installation.rst
	remote_sensing.rst
	Tutorials.rst
	Interface.rst
	thematic_tutorials.rst
	semi-automatic_OS.rst
	FAQ.rst
