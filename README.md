# Substance Designer Enfusion Texture Map Graphs
I've created a number of Substance Designer graphs for those who wish to convert/merge their PBR Texture maps into their Enfusion Engine Compatible Counterparts.

I made these mainly for those who do not have Substance Painter or Designer and do not wish to manually convert/merge their maps using photo editing tools such as Photoshop. 
You can download and install [Substance Player](https://substance3d.adobe.com/documentation/sp31/substance-player-2294742.html) free of charge to open and use the .SBSAR files provided in the repository. 

## Examples
###### OpenGL Tangent Space (Y+) to DirectX Tanget Space (Y-)
![OpenGL to DirectX](/Examples/OpenGL_DirectX.png)
You can use this to convert your OpenGL Normal Maps to DirectX Normal Maps which are used in Enfusion. 
If you already have DirectX Normal Maps you can ignore this completely. C:

###### BaseColor and Roughness to BCR Map
![BaseColor & Roughness to BCR](/Examples/BCR.png)
You can use this to merge your Base Color and Roughness Maps into a single BCR Map which are used in Enfusion.

###### DirectX Normal, Metallic/Height and AO to NMO/NHO Map
![DirectX Normal, Metallic/Height & AO to NMO/NHO](/Examples/NMO_NHO_DirectX.png)
You can use this to merge your DirectX Normal, Metallic/Height and AO Maps into a single NMO/NHO Map which are used in Enfusion.
<br> Use a Metallic Map for NMO or a Height Map for NHO.

###### OpenGL Normal, Metallic/Height and AO to NMO/NHO Map
![OpenGL Normal, Metallic/Height & AO to NMO/NHO](/Examples/NMO_NHO_OpenGL.png)
You can use this to merge your OpenGL Normal, Metallic/Height and AO Maps into a single NMO/NHO Map which are used in Enfusion.
<br> Use a Metallic Map for NMO or a Height Map for NHO.

This directly converts your OpenGL Normal Map into DirectX in the process if you are not feeling inclined to use the converter above before merging.
If you already have DirectX Normal Maps you can ignore this completely. C:
