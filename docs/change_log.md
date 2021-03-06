# Changelog and Roadmap
_Please note that by purchasing PBR Painter you will have access to every update that is released, indefinitely and for no extra cost._

## Changelog

####Compatible with Blender v2.83, 2.90, 2.91 and 2.92:

- v1.1.0:
	- New option to paint a procedural texture for each separate PBR channel (noise, voronoi, musgrave or wave), with tools to tune/scale/rotate these as necessary
	- Additional mask options (procedural noise, voronoi, musgrave or wave) that can be used in combination with all currently available masks
	- New autosave feature which, when turned on, automatically saves modified textures periodically, to avoid accidentally losing work
	- New duplicate layer button
	- Optional color ramp node when using a roughness, specular or metallic texture, for fine-tuning the texture (e.g. make a roughness texture more glossy)
	- Box mapping now available for imported textures, with access to a seam blend slider for creating seamless materials
	- New bake button to be used for baking the current material textures without having to use the merge visible button
	- Improved naming of baked textures to be more specific and streamlined
	- Option to adjust normal strength for each layer individually
	- Bump mapping available as an option in single pass layers
	- New button to instantly invert any color ramp in the addon.

- v1.0.4:
	- Fixed bug that was occasionally causing an error when switching between _paint_ and _erase_, or when adding a layer
	- Introduced the option to change the _blend type_ between layers, for each channel in a layer

- v1.0.3:
	- Reduced dependency on Blender operations for better compatibility with future Blender versions

- v1.0.2: Release version

## Roadmap

#### Completed
- v2.0.0:
	- Major overhaul of addon for a huge boost to performance
	- Restructure UI for a more intuitive, more user-friendly and less busy interface
	- Introduce option for importing a height/bump map in the normal channel
	- Introduce a brand new masking system, using layered system to build complex and highly-specific masks
	- Introduce more options for each specific mask (which can individually be added to the layered setup)
	- Introduce the option to use a custom layer, which lets you build your own layer from scratch using your own node setups, which can then be painted as a layer as per normal (important for advanced users who need highly specific node setups)
	- Introduce copy/paste functions for procedural texture setups, for copying between channels and/or between layers
	- Improve how deleted layers are stored for improved addon performance and efficiency

#### To Do
- Introduce automated external texture saving after baking using a user-defined file subdirectory
- Much more, depending on user feedback (keep it coming!)...
