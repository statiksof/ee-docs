

.. _b2drop::

Sharing with B2DROP
===================

EUDAT B2DROP is being integrated within ECAS for two reasons:

* Users can share their *Notebooks*, *data* or *code* with others
* Sensitive or private data can be pushed to a private B2DROP repository and are available only for the owner.

In both cases, files from B2DROP are visible to the user in his Jupyter workspace.
When you login to ECAS and open a jupyter notebook, two B2DROP directories are mounted: *b2drop-shared* and *b2drop-private* respectively.

Movind data to the shared repositories is performed in different ways:

* Using the *share* button (only for notebooks)
* Using the *move* button to move files from a directory to the b2drop-* repository.
* If notebooks or Text files are created directly into b2drop-* repository, they will be also available in B2DROP.

 

.. _requirements::

Requirements
------------

.. _public_b2drop::

Shared B2DROP repository
------------------------

The shared B2DROP repository is for sharing files between ECAS users.
The link to the repository is sent to the users after the completion of the registration step.

This repository is not conceived for storing data from computing process.
It is principally intended for sharing small-sized files such as jupyter notebooks or scripts.

.. _private_b2drop::

Private B2DROP repository
-------------------------

The *b2drop-private* is synced with the private B2DROP account of the user.
Here, users can put their private data (files).
