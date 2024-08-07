# Sample Meshes

This directory contains sample meshes that might be useful across the project, in both
tests and examples. These are simple test cases for stress-testing and prototyping 
and are not meant to be high-quality 3D examples.

## Flat-shaded Ico Sphere

**Filenames**: [ico_flat.obj](ico_flat.obj), [ico_flat.usda](ico_flat.usda).

**Source**: this mesh is an ico sphere that was authored in Blender with flat shading.

**Formats**: was exported as both `obj` and `usda` (ascii) from Blender.

**Sanity checks**: displays correctly as `obj` and `usda` imported into Blender3.1 and as `usda` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/ico_flat.jpg">

**Attributes** of the single mesh in this file:
* Vertices: 42
* Faces: 80 triangles
* Materials: one simple material applied to all faces
* Normals: for flat shading (same normal for all vertices of a face)
* UVs

<div style="clear:both"></div>

## Smooth-shaded Ico Sphere

**Filenames**: [ico_smooth.obj](ico_smooth.obj), [ico_smooth.usda](ico_smooth.usda). 

**Source**: this mesh is an ico sphere that was authored in Blender with smooth shading.

**Formats**: was exported as both `obj` and `usda` (ascii) from Blender.

**Sanity checks**: displays correctly as `obj` and `usda` imported into Blender3.1 and as `usda` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/ico_smooth.jpg">

**Attributes** of the single mesh in this file:
* Vertices: 42
* Faces: 80 triangles
* Materials: one simple material applied to all faces
* Normals: for smooth shading
* UVs

<div style="clear:both"></div>

## Textured Fox

**Filenames:** [fox.obj](fox.obj), [fox.usdc](fox.usdc).

**Source:** this file is a simiplified version of TurboSquid ID 1073771, which NVIDIA has licensed with distribution rights. *By using this TurboSquid model, you agree that you will only use the content for research purposes only. You may not redistribute this model.*

**Formats**: the original format is `obj`, which was converted to `usdc` (binary) using Blender exporter.

**Sanity checks**: displays correctly as `obj` and `usdc` imported into Blender3.1 and as `usdc` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/fox.jpg">

**Attributes** of the single mesh in this file:
* Vertices: 5002
* Faces: 10000 triangles
* Materials: one simple material with texture applied to all faces
* Normals: for smooth shading
* UVs.

<div style="clear:both"></div>

## Multi-Material Pizza

**Filenames:** [pizza.obj](pizza.obj), [pizza.usda](pizza.usda).

**Source:** this file was authored in Blender with pizza texture taken from a [royalty-free photo by Rene Strgar](https://www.pexels.com/photo/italian-style-pizza-13814644/).

**Formats**: was exported as both `obj` and `usda` (ascii) from Blender.

**Sanity checks**: displays correctly as `obj` (not usd) imported into Blender3.1 and as `usda` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/pizza.jpg">

**Attributes** of the single mesh in this file:
* Vertices: 482
* Faces: 960 triangles
* Materials: one simple material and one texture material applied to groups of faces
* Normals: for smooth shading
* UVs

<div style="clear:both"></div>

## Armchair Quad Meshes

**Filenames:** [armchair.obj](armchair.obj), [armchair.usdc](armchair.usdc).

**License:** this model is released under [Creative Commons — Attribution 4.0 International — CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) License. 

**Formats**: was exported as both `obj` and `usdc` (binary) from Blender; usd format contains a transform. 

**Sanity checks**: displays correctly as `obj` imported into Blender3.1 and as `usdc` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/armchair.jpg">

**Attributes** of the three mesh objects:
1. Mesh 0: Back_LP
   * Vertices: 4146, Faces: 4144 quads, normals, UVs
   * Materials: one textured material (yellow)
2. Mesh 1: Sides_LP
    * Vertices: 912, Faces: 912 quads, normals, UVs
    * Materials: one textured material (white)
3. Mesh 3: Seat_LP
    * Vertices: 4146, Faces: 4144 quads, normals, UVs
    * Materials: same material as for Mesh 0

<div style="clear:both"></div>

## Quad Multi-Object Multi-Material Amsterdam

**Filenames:** [amsterdam.obj](amsterdam.obj), [amsterdam.usda](amsterdam.usda).

**Source:** this stylized city was authored in Blender, it contains simple materials and no textures.

**Formats**: was exported as both `obj` and `usda` (ascii) from Blender.

**Sanity checks**: displays correctly as `obj` imported into Blender3.1 and as `usda` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/). 

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/amsterdam.jpg">

**Attributes** of the 18 meshes in this file:
* Vertices: 4, 98, 98, 98, 386, 386, 98, 8, 98, 98, 98, 4, 4, 4, 386, 98, 4, 4
* Faces (all quads): 1, 96, 96, 96, 384, 384, 96, 6, 96, 96, 96, 1, 1, 1, 384, 96, 1, 1
* Materials: 14 simple materials, with all faces of each mesh bound to a single material
* Normals
* UVs

<div style="clear:both"></div>

## Avocado, Multi-format

**Filenames:** [avocado.gltf](avocado.gltf),  [avocado.obj](avocado.obj),  [avocado.usda](avocado.usda).

**Source**: originally obtained from [KhronosGroup](https://github.com/KhronosGroup/glTF-Sample-Models/tree/main/sourceModels/Avocado) source file, processed in Blender and 
manually to obtain consistent reference files.

**License**: Licensed under [Creative Commons CC0 License](http://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, Microsoft has waived all copyright and related or neighboring rights to this asset.

**Formats**: was exported as `gltf`, `usda` (ascii) and `obj` from Blender.

**Sanity checks**: displays correctly in Blender 3.1 in all formats and as `usda` imported into [NVIDIA Omniverse](https://www.nvidia.com/en-us/omniverse/).

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/avocado.jpg">

**Attributes** of the single avocado mesh:
* Vertices: 406
* Faces: 682 triangles
* Materials: single material with albedo, normals and roughness/metallic texture
* Normals and UVs are consistent across `.obj`, `.gltf`, and `.usd` formats

## Simple Muscle, Folder With Files

**Filenames:** [simple_muscle.mtl](simple_muscle.mtl),  [simple_muscle.obj](simple_muscle.obj), [simple_muscle_vol_pts.pt](simple_muscle_vol_pts.pt), [simple_muscle_fibers.pt](simple_muscle_fibers.pt).

**Source**: originally obtained mesh [EMU](https://arxiv.org/abs/2006.08821) examples.

**License**: Licensed under [Creative Commons CC0 License](http://creativecommons.org/publicdomain/zero/1.0/). To the extent possible under law, Microsoft has waived all copyright and related or neighboring rights to this asset.

**Formats**: was exported as `obj` from Blender. materials were painted on in Blender. Volumetric points were generated via TetWild and fiber directions were generated using heat flow over the muscle volume.

**Sanity checks**: displays correctly in Blender 3.6 and in Meshlab.

<img width="30%" style="padding:0 20px 0 0; float: left" src="renders/simple_muscle.jpg">

**Attributes** of the simple_muscle:
*Vertices: 4624
*Faces: 9112
*Vol_pts: volumetric sample points
*Fibers: fiber directions based on heat flow for each vol pt
