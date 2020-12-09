Overview
========

Kaolin library
--------------

NVIDIA Kaolin library provides a PyTorch API for working with a variety of 3D representations and includes a growing collection of GPU-optimized operations such as modular differentiable rendering, fast conversions between representations, data loading, 3D checkpoints and more.

It is composed of multiple modules:

Ops:
^^^^

:ref:`kaolin/ops<kaolin.ops.rst>` contains operators for efficient processing functions of batched 3d models and tensors.

We provide, conversions between 3d representations, primitives batching of heterogenenous data, and efficient mainstream functions on meshes and voxelgrids

I/O:
^^^

:ref:`kaolin/io<kaolin.io.rst>` contains functionality to interact with files.

We provide, importers and exporters to popular format such as .obj and .usd, but also utility functions and classes to preprocess and cache datasets with specific transforms.

Metrics:
^^^^^^^^

:ref:`kaolin/metrics<kaolin.metrics.rst>` contains functions to compute distance and losses such as point_to_mesh distance, chamfer distance, IoU, or laplacian smoothing. 

Render:
^^^^^^^

:ref:`kaolin/render<kaolin.render.rst>` provide functions related to differentiable rendering, such a DIB-R rasterization, application of camera projection / translation / rotation, lighting, and textures.

3D Checkpoints and Visualization:
^^^^^^^^^^

:ref:`kaolin/visualize<kaolin.visualize.rst>` contains utilities for writing 3D checkpoints for visualization.

Currently we provide timelapse exporter that can be quickly picked up by the Omniverse Kaolin App (see `Kaolin developer page<https://developer.nvidia.com/kaolin>`_)

Utils:
^^^^^^

:ref:`kaolin/utils<kaolin.utils.rst>` contains utility functions to help development of application or research scripts.

We provide functions to display and check informations about tensors, and features to fix seed.    
