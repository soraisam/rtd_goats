.. _about-goats:

GOATS: Gemini Observation and Analysis of Targets System
========================================================

**GOATS** is a browser-based user interface providing end-to-end automation of the entire time-domain/multi-messenger astronomy follow-up process -- from target selection, over triggering of follow-up observation, over data retrieval, to data reduction and analysis. 

.. _goats-capabilities:
.. figure:: /images/goats_general.png
   :alt: GOATS capabilities 
   :align: center
   :scale: 80 %

   GOATS will integrate all the software services involved in time-domain and multi-messenger astronomy follow-up. 

It serves as a Target and Observation Manager (TOM) that can be used out-of-the-box. It is built using the |TOMToolkit|, however it, in itself, is not a software development kit but rather a fully-assembled TOM. Its main motivation is to lower the entry barrier for the user community.  

.. _goats-schematic:
.. figure:: /images/goats_with_lab.jpg
   :alt: GOATS building blocks 
   :align: center
   :scale: 80 %

   Schematic of GOATS, highlighting its building blocks. 

The main components of GOATS are shown in :numref:`goats-schematic` above. It is primarily directed towards Gemini follow-up observations, while leveraging complementary services (see :ref:`below <building-blocks>`) for time-domain astronomy built by programs across the larger NOIRLab organization. 

.. _building-blocks:

Building blocks of GOATS
========================
GOATS relies on the following components - 

* |ANTARES| : NOIRLab's alert broker for target selection.
* |TOMToolkit| : Software for building and customizing TOMs developed by the Las Cumbres Observatory. It includes a plugin for triggering Gemini. 
* |GOA| : Gemini data archive.
* |DRAGONS| : Gemini data reduction software.
* |Dlab| : NOIRLab's science platform, which provides access to various legacy catalogs and a JupyterHub environemnt.  

.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: About GOATS


.. toctree::
   :maxdepth: 3
   :hidden:
   :caption: Quickstart

   installation.rst



