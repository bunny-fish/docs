.. A "how to" for setting up Python to support technical documentation generation with Sphinx.

How to Set Up Python
====================

Start by verifying that Python is installed and accessible by checking the installed version.

``python --version``

Set up a virtual environment using the ``venv`` command from the Python standard library.

``python -m venv .venv``

The arguement ``.venv`` is used to identify the virtual environment created.  A directory named ``.venv`` is created to house all of the data needed for the new virtual environment.  Next, the virtual environment needs to be activated, which is done by running a script in the created directory.

``.venv\Scripts\activate``

The PowerShell prompt should change with the addition of a ``(.venv)`` to the left of the prompt.  Now, the pacakges required can be installed into the virtual environment.

``python -m pip install sphinx sphinx-rtd-theme``

The virtual environment will need to be activated using the ``activate`` script each time to use Sphinx to generate documentation output.
