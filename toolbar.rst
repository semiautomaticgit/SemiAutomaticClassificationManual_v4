.. _toolbar:

******************************
Toolbar
******************************

.. |br| raw:: html

 <br />

.. figure:: _static/toolbar.jpg
	:align: center
	
	:guilabel:`Toolbar`
		
The ``Toolbar`` allows for the selection of the ``Input image``, and includes several buttons for opening the main functions of the :ref:`main_interface_window`.

The following video shows this tool.

.. raw:: html

	<iframe allowfullscreen="" frameborder="0" height="360" src="http://www.youtube.com/embed/nZffzX_sMnk?start=140&rel=0" width="100%"></iframe>

http://www.youtube.com/watch?t=140&v=nZffzX_sMnk

Alternative video link
https://archive.org/details/video_basic_tutorial_1?start=140

|br|

[P] = Configuration stored in the active project of QGIS

[Q] = Configuration stored in QGIS registry

* |plugin|: show the :ref:`main_interface_window` and display the :ref:`roi_dock` and the :ref:`classification_dock`;
* |band_set|: open the :ref:`band_set_tab`;
* ``Input image`` [P]: select the input image from a list of multi-spectral images loaded in QGIS; input image can be a multi-spectral raster or a set of single bands defined in the :ref:`band_set_tab` (if the :ref:`band_set_tab` is defined, then this list will contain the item `<< band set >>`;
* |refresh|: refresh image list;
* ``RGB=`` [P]: select a color composites that is applied to the ``Input image`` ; new color composites can be defined typing the band numbers separated by ``-`` or ``;`` or ``,`` (e.g. RGB = 4-3-2 or RGB = 4;3;2 or RGB = 4,3,2);
* < ``Show`` >: show/hide the input image in the map;
* |cumulative_stretch|: display the input image stretching the minimum and maximum values according to cumulative count of current extent;
* |std_dev_stretch|: display the input image stretching the minimum and maximum values according to standard deviation of current extent;
* |sign_plot|: open the :ref:`spectral_signature_plot`;
* |tools|: open the :ref:`tools_tab`;
* |preprocessing|: open the :ref:`pre_processing_tab`;
* |postprocessing|: open the :ref:`post_processing_tab`;
* |bandcalc|: open the :ref:`band_calc_tab`;
* |settings|: open the :ref:`settings_tab`;
* |guide|: open the online user manual in a web browser;
* |help|: open the `Online help <http://fromgistors.blogspot.com/p/ask-for-help.html>`_ in a web browser; also, a `Facebook group <https://www.facebook.com/groups/661271663969035/>`_ and a `Google+ Community <https://plus.google.com/communities/107833394986612468374>`_ are available for sharing information and asking for help about SCP.

.. |plugin| image:: _static/semiautomaticclassificationplugin.png
	:width: 20pt
	
.. |refresh| image:: _static/refresh_button.jpg
	:width: 20pt
	
.. |band_set| image:: _static/semiautomaticclassificationplugin_bandset_tool.png
	:width: 20pt

.. |cumulative_stretch| image:: _static/semiautomaticclassificationplugin_bandset_cumulative_stretch_tool.png
	:width: 20pt

.. |std_dev_stretch| image:: _static/semiautomaticclassificationplugin_bandset_std_dev_stretch_tool.png
	:width: 20pt

.. |sign_plot| image:: _static/semiautomaticclassificationplugin_sign_tool.png
	:width: 20pt

.. |tools| image:: _static/semiautomaticclassificationplugin_roi_tool.png
	:width: 20pt
	
.. |preprocessing| image:: _static/semiautomaticclassificationplugin_class_tool.png
	:width: 20pt
	
.. |postprocessing| image:: _static/semiautomaticclassificationplugin_post_process.png
	:width: 20pt
			
.. |bandcalc| image:: _static/semiautomaticclassificationplugin_bandcalc_tool.png
	:width: 20pt
		
.. |settings| image:: _static/semiautomaticclassificationplugin_settings_tool.png
	:width: 20pt
			
.. |guide| image:: _static/guide.png
	:width: 20pt
				
.. |help| image:: _static/help.png
	:width: 20pt
	