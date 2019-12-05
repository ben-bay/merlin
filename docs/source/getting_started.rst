Getting Started
================

Quick Start
+++++++++++

This setup will work in most cases and can be used to quickly setup Merlin.

Pip-install merlin::

    pip3 install merlinwf


Configuring Merlin
*******************

Once Merlin has been installed, the installation needs to be configured.
Documentiation for merlin configuration is in the :doc:`Configuring Merlin <./merlin_config>` section. 

That's it. To start running Merlin see the :doc:`Merlin Workflows. <./merlin_workflows>`


Install Python Package Dependencies
************************************

Merlin uses Pip to manage Python dependencies. Merlin dependencies can be
found in the requirements directory in the Merlin repository.

To install the standard set of dependencies run::

    (merlin3_7) $ pip install -r requirements.txt

This will install all the required dependencies for Merlin and development
development dependencies.


Installing Merlin
*******************

Merlin can be installed in editable mode. From within the Merlin repository::

    (merlin3_7) $ pip install -e .

Any changes made to the Merlin source code should automatically reflect in the
virtualenv.

.. tip:: If changes to Merlin's source code do not reflect when running Merlin
    try running `pip install -e .` from within the Merlin repository.
