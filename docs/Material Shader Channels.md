
# List of all the available Shader Channels of Cinema4D Materials
Retrieved from C++ SDK: https://developers.maxon.net/docs/Cinema4DCPPSDK/html/mmaterial_8h.html#ac998c8f2ed6a3c0d0ae07b3822c16f9da4cae70ca3e438d9ac3d210e15d9e8ca7

Usage example (Creating a Material and put a shader into its Shader Channel):
```python
  mat = c4d.Material()
  shader = c4d.BaseList2D(c4d.Xcolor)
  
  mat[c4d.MATERIAL_COLOR_SHADER] = shader
  mat.InsertShader(shader)
```
___

## Material Shader Channel types
|       SDK name        | Common Shader name in C4D GUI |
|-----------------------|   :------------------:        |
| __MATERIAL_COLOR_SHADER__	        | _The color channel of the material._
| __MATERIAL_LUMINANCE_SHADER__	    | _The luminance channel of the material._
| __MATERIAL_TRANSPARENCY_SHADER__	| _The transparency channel of the material._
| __MATERIAL_REFLECTION_SHADER__	  | _The reflection channel of the material._
| __MATERIAL_ENVIRONMENT_SHADER__	  | _The environment channel of the material._
| __MATERIAL_BUMP_SHADER__	        | _The bump channel of the material._
| __MATERIAL_ALPHA_SHADER__	        | _The alpha channel of the material._
| __MATERIAL_SPECULAR_SHADER__	    | _The specular channel of the material._
| __MATERIAL_DISPLACEMENT_SHADER__	| _The displacement channel of the material._
| __MATERIAL_DIFFUSION_SHADER__	    | _The diffusion channel of the material._
| __MATERIAL_NORMAL_SHADER__	      | _The normal channel of the material._
