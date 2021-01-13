# Understanding the Main UI Panel
## Before Adding a PBR Layer

When there are no currently active PBR Layers on the material, the UI will look like this and you will be prompted to add a new layer to get started:

![Screenshot](img/ui_no_layers.png)

Go ahead and click the "Add Layer" button to add a new layer:

![Screenshot](img/ui_add_layer.png)

## The UI with Active Layers

Once you've added one or more layers, you will see the complete UI for the addon. This is outlined below:

![Screenshot](img/ui_full.png)

The following tools can be accessed in this main panel:

- __Mask resolution__: Controls the resolution of the mask you will be painting that will be used to perform the multipass PBR painting. Note that this resolution
only affects the _subsequently added_ layer.
- __List of active layers__: Shows all of the active PBR layers associated with the material, in order. That is, layers higher up on the list appear on top in the
material.
- __Layer name__: The (modifiable) name of the currently selected layer, shown in the list.
- __Toggle paint/erase__: Switch between painting and erasing the currently selected layer.
- __Hide layer__: Hide the currently selected layer.
- __New layer__: Add a new layer to the list. Note that the new layer will be added immediately above the currently selected layer.
- __Delete layer__: Delete the currently selected layer. Note that up to 10 layers are stored in the __Deleted Layers__ panel (more on this later).
- __Move layer__: Move the currently selected layer up or down in the list.
- __Merge visible__: Merge all visible layers (more on this later).
- __Save images__: Saves all modified masks to the .blend file. This is important to avoid any loss of work due to unexpected crashes etc.

In addition to these tools, there are also 5 sub-panels which constitute the remainder of the addon: __Texture Maps__, __Texture Mapping__, __Layer Settings__, 
__Other Principled BSDF Inputs__ and __Deleted Layers__. The following sections in this documentation describe what is in these sub-panels in PBR Painter and 
their various functionalities/purposes. __The following sections will be most useful as a reference while you are using the addon.__