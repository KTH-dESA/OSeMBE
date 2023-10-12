OSeMBE - Open Source energy Model Base for the European Union
=============================================================

.. image:: https://zenodo.org/badge/375290763.svg
    :target: https://zenodo.org/badge/latestdoi/375290763

.. image:: https://readthedocs.org/projects/osembe/badge/?version=latest
    :target: https://osembe.readthedocs.io/en/latest/?badge=latest
    :alt: Documentation Status

An OSeMOSYS model of the European Union, Norway, Switzerland, and the United Kingdom

Description
-----------

**OSeMBE** is an energy model base for the European Union developed using the OSeMOSYS Modelling Framework.
The model provides country-detailed representation of the 27 European Union (EU) Member States, Norway, Switzerland and the United Kingdom. The model aims at being used as a multi-regional stakeholders engagement model at the European level.
The development was funded by the European Union’s Horizon 2020 research and innovation programme under grant agreement No 691739.

Setup and Installation
----------------------

To use the model you need to install GLPK and a solver such as CBC, gurobi or CPLEX.

It is recommended to run the dataset in combination with the fast code of OSeMOSYS v1.0.1. To be found here: https://github.com/OSeMOSYS/OSeMOSYS_GNU_MathProg/releases/download/v1.0.1/osemosys_gnu_mathprog_v1.0.1.zip

It is recomended to use otoole v0.10.0 to handle input and output data. It can be installed by using::
    
    pip install otoole==0.10.0

For the visualisation scripts you should have an environment with the following dependencies:

- `python` >= 3.6
- `pandas`
- `plotly`

From this model version onwards `Carbon Capture and Storage (CCS)` are available in **OSeMBE**. This makes it necessary that the model can handle negative emissions. Therefore, some minor modifications were necessary to the OSeMOSYS code. To run the model the OSeMOSYS code that can be found `here <https://github.com/HauHe/OSeMOSYS_GNU_MathProg/tree/osembe/src>`_ should be used.

Folder structure
----------------

- Input data are stored as `datapackages` in the `input_data` folder

Documentation
-------------

A more detailed documentation of OSeMBE can be found here: https://osembe.readthedocs.io/en/latest/
The OSEMBE codes of the different sets can be found in the documentation. The codes can also be decoded using the script code_decipherer.

Licensing
---------
OSeMBE is released under the terms of a CC-BY-4.0 International License Agreement. The license text can be found in the LICENSE.

Citation
--------

If you wish to use, extend or otherwise build upon the work contained within this repository, you are
welcome to do so, provided you abide by the terms of the licenses detailed above.

Please cite this work using the **DOI** indicated above.
