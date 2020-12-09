.. _kaolin.io.usd:

kaolin.io.usd
=============

Universal Scene Description
---------------------------

Universal Scene Description (USD) is an open-source 3D scene description file format developed by Pixar and designed to be versatile, extensible and interchangeable between different 3D tools.

Single models and animations as well as large organized scenes composed of any number of assets can be defined in USD, making it suitable for organizing entire datasets into interpretable,
subsets based on tags, class or other metadata label.

As a first step to familiarizing yourself with USD, we suggest following this `tutorial <https://developer.nvidia.com/usd>`_.
More tutorials and documentation can be found `here <https://graphics.pixar.com/usd/docs/Introduction-to-USD.html>`_.


Creating a Mesh Dataset from a USD Scene
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Kaolin supports importing/export meshes, voxelgrids and pointclouds from/to USD.

Let's use Pixar's `KitchenSet <http://graphics.pixar.com/usd/downloads.html>`_ for our example.

# TODO Add image

Next we will create a mesh dataset from this scene. First, we need 
to set our environment variables:

.. code-block:: bash

    >>> source setenv.sh

This step is required for any interactions with USD. Now, we can create our dataset:

.. code-block:: python

    >>> from kaolin.io import usd
    >>> usd_meshes = usd.import_meshes(usd_filepath='./data/Kitchen_set/Kitchen_set.usd')
    >>> len(usd_meshes)
    740

And just like that, we have a dataset of 740 diverse objects for our use!
Let's see what they look like.

    # TODO Add visualization example


And opening the USD in your favourite USD viewer with a bit of styling, we get:

    # TODO

# TODO Add training example (classification or something else very simple) with visualization

Viewing USD Files
~~~~~~~~~~~~~~~~~
USD files can be visualized using Pixar's USDView which you can obtain by visiting 
`https://developer.nvidia.com/usd <https://developer.nvidia.com/usd>`_ and selecting the 
corresponding platform under *.USD Pre-Built Libraries and Tools*. Note, USDView only supports
python 2.7.

Some Notes
~~~~~~~~~~

- Currently, \*.usd and \*.usda file extensions are supported.

API
---

.. automodule:: kaolin.io.usd
    :platform: Windows-x86_64, Linux-x86_64
    :members:
