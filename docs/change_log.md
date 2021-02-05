# Changelog and Roadmap
_Please note that by purchasing PBR Painter you will have access to every update that is released, indefinitely and for no extra cost._

## Changelog

####Compatible with Blender v2.91:

- v1.0.4:
	- Fixed bug that was occasionally causing an error when switching between _paint_ and _erase_, or when adding a layer
	- Introduced the option to change the _blend type_ between layers, for each channel in a layer, as per video below:
<iframe width="560" height="315" src="https://www.youtube.com/embed/dMB1W2RppWw" frameborder="0" allow="accelerometer; autoplay; 
clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

- v1.0.3:
	- Reduced dependency on Blender operations for better compatibility with future Blender versions

- v1.0.2: Release version

## Roadmap

#### Completed (coming in v1.1)
- Introduce _duplicate layer_ button
- Introduce optional color ramp node when using a roughness, specular or metallic texture, for fine-tuning the texture (e.g. make a roughness
texture more glossy)
- Major code refactoring for better efficiency
- Introduce additional mask options (procedural noise, voronoi, musgrave or wave)
- Introduce a _bake all_ button to be used for baking the current material textures _without_ having to use the __merge visible__ button.
- Introduce the option to generate a noise texture for each separate PBR channel (noise, voronoi, musgrave or wave), with tools to tune these as necessary
- Change naming of merged layer textures to be more specific (e.g. change from "Merged_Albedo" to "Suzanne_Albedo_4K", where "Suzanne" is the object name and
"4K" is the specified resolution)
- Change some terminology in the UI (e.g. map -> texture) to be clearer
- Change how normals are mixed (introduce a normal map into each layer, allowing 'normal strength' to be adjusted per layer)

#### To do
- Introduce flexibility with regards to incorporating PBR Painter with manually developed shader node trees
- Much more, depending on suggestions/feedback received...