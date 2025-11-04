# Quaternious Utility Library for Unity

Helper scripts to help import some of Quaternious packs, list of utils are below

## Install guide for Utils

2 Seperate Ways

1. Download the Unitypackage file and import

2. Drag and drop the script anywhere inside your asset folder

Enjoy!

## Universal Animation Library Importer

Applies needed steps to the universal animation library after its imported
Applies baked axis conversion
Sets Animation Type
Sets Root motion node
Goes over the imported animations and applies looping to the correct ones

## User Guide
Select the Universal Animation Library Asset
Go to "Tools/QuaterniousUtility/" and select "Apply import steps to Universal Animation Library"
Click Apply at the bottem of the inspector (or click off the Animation Library and click save in dialog box)
Done!


## Collision Prefab Creator

Transforms Quaternious source models and collisions and puts them into a Prefab asset, ready to use in unity

## User Guide

Select the models of quaternius that you want to combine the collision meshes for, then go to Tools/Apply collision Prefab
this is non-destructive, and only creates new prefabs at (OS Independant) "Assets/Prefabs/{model_name}_withCollisions



# Notice 

The collision folder must be in the same folder as the model source fbx files

Some of quaternious's Models do not have collisions, or are seperated parts of the other models. This will still create a prefab, but wont apply a collider. 

the collisions are by name only, using Collision_ as the start for each of the colliders. if the naming scheme is the same, it will work for other packs.
if it isnt the same, you just need to change the (collision+(model) name part of the collisionpath to reflect the new naming scheme.


# Currently supported Packs

[Medieval Village Megakit](https://quaternius.com/packs/medievalvillagemegakit.html)


