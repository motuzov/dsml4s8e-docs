Welcome to DSML4s8e's documentation!
===================================

The library name is a abbreviation of Data Science / ML flow standalone.
(Data Science / ML) -> **DSML**
+
flow -> ****(4) -> **4**
+
standalone -> s********e -> **s8e**
=
**DSML4s8e**

Dsml4s8e is a Python library that extends Dagster to help manage the ML workflow around Jupyter notebooks development.

**DSML4s8e** addresses issues: 

 1. Building of pipelines from **standalone** notebooks
 2. Standardizing a structure of ML/DS pipeline projects to easy share and continuous improve them
 3. Managing pipelines data in a continuous improvement process of its

Dsml4s8e designed to support the following workflow:
 1. Define a project structure and a structure of the pipeline data catalog  for your pipeline by using class `Storage Catalog ABC`.
 2. Develop **standalone** Jupyter notebooks corresponding specification requirements.
 3. Difine a **pipeline** -- a sequence of notebooks and deloy the pipelien in vary environments(experimental/test/prod).
 4. Execute pipelines many times with different configurations in vary environments and on vary infrastructure..

Check out the :doc:`usage` section for further information, including
how to :ref:`installation` the project.

.. note::

   This project is under active development.

Contents
--------

.. toctree::

   usage
   api
