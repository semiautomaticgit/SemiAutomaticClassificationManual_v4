.. _spectral_signature_plot:

******************************
Spectral Signature Plot
******************************

.. |br| raw:: html

 <br />

The ``Spectral Signature Plot`` window allows for the displaying of spectral signature plots, which are the signature values (usually reflectance) as a function of wavelength. 
Signatures can be added to the ``Spectral Signature Plot`` through the :ref:`roi_dock` and the :ref:`classification_dock`.
Only signatures checked in the :ref:`signature_list_plot` are displayed (which is independent from :ref:`signature_list` in the :ref:`classification_dock` ).

.. figure:: _static/spectral_signature.jpg
	:align: center
	:width: 500pt
	
	:guilabel:`Spectral Signature Plot`

.. _signature_list_plot:

Plot Signature list
----------------------

* Table fields:
	* ``S`` : checkbox field; if checked, then signature is displayed in the plot;
	* ``MC ID`` : Macroclass ID;
	* ``MC Info`` : Macroclass Information;
	* ``Class ID`` : Class ID;
	* ``C Info`` : Class Information;
	* ``Color`` : color field; double click to select a color for the plot;
* ``Plot`` :math:`\sigma` : if checked, plot the standard deviation for each signature;
* [ ``Remove signatures`` ]: remove highlighted signatures from this list;
* [ ``Fit to data`` ]: resize the plot to fit to all the data;
* ``Calculate spectral distances`` : if checked, calculate the following spectral distances:
	* :ref:`Jeffries_Matusita_distance`;
	* :ref:`spectral_angle`;
	* :ref:`euclidean_distance`;
	* :ref:`Bray_Curtis_similarity`.
	
.. _signature_plot:

Plot
^^^^^^^^^^^^^^^^^^^^^^^^^

It is possible to move the legend inside the plot with the mouse.
	
* Plot commands (from Matplotlib):
	* |m_home|: Reset to original view;
	* |m_back|: Back to previous view;
	* |m_forward|: Forward to next view;
	* |m_pan|: Pan axes with left mouse, zoom with right;
	* |m_zoom|: Zoom to rectangle;
	* |m_sub|: Unused;
	* |m_save|: Save plot to a figure (e.g. JPG file); 
	* |m_edit|: Unused.

|br|

.. |m_home| image:: _static/matplotlib_home.jpg
	:width: 20pt
	
.. |m_back| image:: _static/matplotlib_back.jpg
	:width: 20pt
	
.. |m_forward| image:: _static/matplotlib_forward.jpg
	:width: 20pt
	
.. |m_pan| image:: _static/matplotlib_pan.jpg
	:width: 20pt
	
.. |m_zoom| image:: _static/matplotlib_zoom.jpg
	:width: 20pt
	
.. |m_sub| image:: _static/matplotlib_sub.jpg
	:width: 20pt

.. |m_save| image:: _static/matplotlib_save.jpg
	:width: 20pt
	
.. |m_edit| image:: _static/matplotlib_edit.jpg
	:width: 20pt
	

.. figure:: _static/example_plot.jpg
	:align: center
	:width: 500pt

	:guilabel:`Spectral Signature: Example of spectral signature plot`
	
.. _signature_details:

Signature details
^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: _static/spectral_signature_details.jpg
	:align: center
	:width: 500pt
	
	:guilabel:`Spectral Signature: Signature details`

Display the details about spectral signatures (i.e. Wavelength, Values, and Standard deviation).

This is useful for comparing the values of different spectral signatures or pixels.

.. figure:: _static/example_details.jpg
	:align: center
	:width: 500pt

	:guilabel:`Spectral Signature: Example of signature details`
		
.. _spectral_distances:

Spectral distances
^^^^^^^^^^^^^^^^^^^^^^^^^

.. figure:: _static/spectral_signature_distances.jpg
	:align: center
	:width: 500pt
	
	:guilabel:`Spectral Signature: Spectral distances`

Display spectral distances for each combination of signatures, if ``Calculate spectral distances`` is checked in :ref:`signature_list_plot` .
It is useful for assessing ROI separability (see :ref:`spectral_distance_definition`).

The following spectral distances are calculated :

* Jeffries-Matusita distance:  range [0 = identical, 2 = different]; useful in particular for :ref:`max_likelihood_algorithm` classifications;
* Spectral angle: range [0 = identical, 90 = different]; useful in particular for :ref:`spectra_angle_mapping_algorithm` classifications;
* Euclidean distance: useful in particular for :ref:`minimum_distance_algorithm` classifications;
* Bray-Curtis similarity [%]: range [0 = different, 100 = identical]; useful in general.
	
Values are displayed in red if signatures are particularly similar.
	
.. figure:: _static/example_distance.jpg
	:align: center
	:width: 500pt
	
	:guilabel:`Spectral Signature: Example of spectral distances`
