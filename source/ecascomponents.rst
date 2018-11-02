.. _components::

ECAS Components
===============


Architecture
------------

.. image:: images/new-ecas-architecture.png

Involved services/frameworks
----------------------------

* **Ophidia:** is a research project on big data analytics for eScience. It provides a framework for parallel I/O and data analysis, an array-based storage model and a hierarchical storage organization to partition and distribute multidimensional scientific datasets.
* **B2Handle:** the b2handle Python library is a client library for interaction with a Handle System server. The role of B2Handle is to enable PID-provenance support
* **B2DROP and B2SHARE:** are EUDAT services that provide a flexible and open data sharing. **ECAS** users will be able to access/share data and notebooks.
* **EOSCHUB AAI:** besides LDAP, *B2ACCESS*, *EGI Check in* and *Indigo IAM* can be used to login to the **ECASLab**.
* **ESGF:** provides a robust software stack covering different areas. The most significant for ECAS is *Data node*. Actually, CMIP5 and soon CMIP6 data are available from ESGF data pool at **CMCC** and **DKRZ**.
