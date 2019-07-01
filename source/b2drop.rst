.. _EUDAT B2DROP:

Sharing with B2DROP
===================

EUDAT B2DROP is integrated within ECAS for two reasons:

* Users can share their *Notebooks*, *data* or *code* with others
* Sensitive or private data can be pushed to a private B2DROP repository and are available only for the owner.

In both cases, files from B2DROP are visible to the user in his Jupyter workspace.
When you login to ECAS and open a jupyter notebook, two B2DROP directories are mounted: *b2drop-shared* and *b2drop-private* respectively.

Moving data to the shared repositories is performed in different ways:

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

How to mount your B2DROP
~~~~~~~~~~~~~~~~~~~~~~~~

Please, follow these steps to mount your own B2DROP repository into the jupyter notebook.

1. Generate *app password* from B2DROP
2. Log in to ECASLab
3. Go to *conf*
4. Put the credentials (in two lines) generated from (1) in the *env* file and save it
5. Open *mount-your-b2drop.ipynb* and execute it.
6. DONE!

.. Note:: You don't need to repeat the above steps each time you open your notebook. B2DROP will be still mounted unless credentials have been changed or your notebook is deleted.

The B2DROP Ophidia operator (OPH_B2DROP)
----------------------------------------

It uploads a file onto a B2DROP remote folder. Note that in order to be able to use the operator, a netrc file with the credentials to B2DROP is required.
For more information about this operator, please visit this `link <http://ophidia.cmcc.it/documentation/users/operators/OPH_B2DROP.html?highlight=b2drop>`_


