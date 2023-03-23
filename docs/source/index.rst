Usage
=====

Som en innledende merknad
er det rimelig
 å si at
 dete er mest
 for å fylle plass
 i en uttestingssituasjon
 så vet man det altså

.. _installation:

Installation
------------

Selve produktet oppgis
ikke her sånn uten videre
men man kn alltids test
hvordan det vil være å innhente
en slik informasjon senere
nårdet er tid

To use Lumache, first install it using pip:

.. code-block:: console

   (.venv) $ pip install lumache

Creating recipes
----------------

To retrieve a list of random ingredients,
you can use the ``lumache.get_random_ingredients()`` function:

.. autofunction:: lumache.get_random_ingredients

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

Svein
-----

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

.. toctree::

   usage
   api
   ipa

