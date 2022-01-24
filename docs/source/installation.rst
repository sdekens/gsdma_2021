Installation 
=============

To clone the repository and setup the environment for using this project
:

.. code-block:: bash

   $ git clone git@github.com:kaufmanno/gsdma_2021.git
   $ cd gsdma_2021/
   $ pipenv shell
   $ pipenv install

To view installed dependencies, see the
`Pipfile <https://github.com/kaufmanno/gsdma_2021/blob/master/Pipfile>`__.
Be aware that using *pipfile install* actually installs from the
Pipfile.lock file. Use the –skip-lock option if you want to use the
Pipfile instead.

Install the different libraries with "pip install"
*geopandas
*pyvista
*pyacd
*numpy
