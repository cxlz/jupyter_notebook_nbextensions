# jupyter_notebook_nbextensions

nbextensions_configurator: https://github.com/Jupyter-contrib/jupyter_nbextensions_configurator
Installation
conda install -c conda-forge jupyter_nbextensions_configurator
pip install jupyter_nbextensions_configurator

Enable
jupyter nbextensions_configurator enable --user

As a tab on the dashboard
http://localhost:8888/tree#nbextensions_configurator

jupyter_contrib_nbextensions: https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html
1. Install the python package
conda install -c conda-forge jupyter_contrib_nbextensions
pip install jupyter_contrib_nbextensions

2. Install javascript and css files
jupyter contrib nbextensions install --sys-prefix --skip-running-check

3. Enabling/Disabling extensions
jupyter nbextension enable <nbextension require path>
jupyter nbextension enable codefolding/main




