.. ECAS documentation master file, created by
   sphinx-quickstart on Mon Aug 20 10:11:45 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. _filesystem::

ECAS File System
================

This sections lists the directories, which are available in the Jupyter notebook.
This important to know what are operations allowed on each of them.

.. _docker volume::

User workspace
--------------

This space is only for the user opening a session at ECAS.
The data and workflows have read-write access and are stored in a specific docker volume at disk.
Even if you close your session or you restart the notebook, data will not be lost.

.. _shared_fs::

Shared with others
------------------

The following directories are read-only directories and you are not allowed to create or save notebooks/data.

* *data*,
* *notebooks*,
* *quickstart* and
* *workflows*

The content of these directories is avalable for all users logged into **ECASLab**.
The **conf** is also a shared directory and contains information on how to mount your private B2DROP into the Jupyter notebook.
This is not recommended to store other files in this directory.

.. _esgf::

ESGF Data Pool
--------------

... Already available but documentation coming soon.

.. _ophidiafs::

Ophidia File System
-------------------

Please go `here <http://ophidia.cmcc.it/documentation/users/vfs/index.html>`_ for more information about the Ophidia filesystem.


