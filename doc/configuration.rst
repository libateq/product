*************
Configuration
*************

The *Product Module* uses some settings from the ``[product]`` section of the
:doc:`configuration file <trytond:topics/configuration>`.

.. _config-product.price_decimal:

``price_decimal``
=================

The ``price_decimal`` setting defines how many decimal places are used when
storing `Products' <concept-product>` unit prices.

.. warning::

   Once the database has been created you cannot reduce this value.

The default value is: ``4``

.. _config-product.uom_conversion_decimal:

``uom_conversion_decimal``
==========================

The value from the ``uom_conversion_decimal`` setting defines the number of
decimal places used when storing the conversion rates and factors between
`Units of Measure <model-product.uom>`.

.. warning::

   Once the database has been created you cannot reduce this value.

The default value is: ``12``
