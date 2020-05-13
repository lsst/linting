########################
Code Linting Environment
########################

This package provides a `pip`_ requirements file which is to install linters or other tools which are used by Travis to check changes being made to DM packages.
The versions of the linters specified in this file should be kept synchronized with those specified in `scipipe_conda_env`_.
Be aware that the Jenkins CI system uses `scipipe_conda_env`_ directly, rather than referring to this repository.
For details, refer to the `Developer Guide`_.

.. _pip: https://pip.pypa.io/en/stable/
.. _scipipe_conda_env: https://github.com/lsst/scipipe_conda_env
.. _Developer Guide: https://developer.lsst.io/stack/adding-a-new-package.html#configuring-github-repositories
