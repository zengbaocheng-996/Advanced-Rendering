# Advanced-Rendering

| Index | Content                    | Detail                                                       |
| ----- | -------------------------- | ------------------------------------------------------------ |
| 01    | Flat and Wireframe Shading | Use screen-space derivatives to find triangle normals<br />Do the same via a geometry shader<br />Use generated barycentric coordinates to create a wireframe<br />Make the wires fixed-width and configurable |
| 02    | Tessellation               | Create hull and domain shaders<br />Subdivide triangles<br />Control how things get tessellated |
| 03    | Surface Displacement       | Adjust vertex positions on the GPU<br />Tessellate shadow geometry<br />Skip tessellating unseen triangles |
| 04    | Bloom                      | Render to a temporary texture<br />Blur via downsampling and upsampling<br />Perform progressive sampling<br />Apply a box filter<br />Add bloom to an image |
| 05    | Depth of Field             | Determine the circle of confusion<br />Create bokeh<br />Focus and unfocus an image<br />Split and merge foreground and background |
| 06    | FXAA                       | Calculate image luminance<br />Find high-contrast pixels<br />Identify contrast edges<br />Selectively blend<br />Search for the end points of edges |
| 07    | Triplanar Mapping          | Remove dependency on UV and tangents<br />Support a generic surface approach<br />Use planar projections<br />Blend between three mappings |

