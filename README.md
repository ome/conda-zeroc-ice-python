# Zeroc Ice Python Conda package for OMERO
[![Anaconda-Server Badge](https://anaconda.org/ome/zeroc-ice36-python/badges/version.svg)](https://anaconda.org/ome/zeroc-ice36-python)

A Conda package for Zeroc Ice Python compatible with OMERO.


## Release
This is a compiled Python 3 64 module.
Most OME Python and Conda projects use Travis-CI for builds and releases, however it has limited support for Windows.
For full cross-platform support (Linux-64, OSX-64, Win-64) Azure Pipelines is used for building and releasing packages for platforms .

Setup:
- Create a new [Azure devops project](https://azure.microsoft.com/en-gb/services/devops/pipelines/)
- Add this repository
- Create a [secret variable](https://docs.microsoft.com/en-us/azure/devops/pipelines/process/variables?view=azure-devops&tabs=yaml%2Cbatch#secret-variables) `ANACONDA_API_TOKEN`
- [Adjust your notifications](https://docs.microsoft.com/en-us/azure/devops/notifications/manage-your-personal-notifications?view=azure-devops&tabs=preview-page) if necessary
