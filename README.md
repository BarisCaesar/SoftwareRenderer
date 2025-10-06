#  Software Renderer

A lightweight **software renderer** written in C++, exploring the core concepts behind modern graphics pipelines — including **depth culling**, **Phong lighting**, **vertex shading**, and **perspective-corrected texture mapping**. 

This renderer is built upon Chili Framework which is a lightweight framework that allows you to create windows and put pixels on the screen.

---

##  Features

-  **Vertex Shaders** – Transform 3D vertices through model, view, and projection matrices.
-  **Geometry Shaders** - Operate on entire primitives (triangles, lines, etc.) to perform geometry-level transformations or generate new shapes.
-  **Pixel Shaders** - Compute the final color of each pixel, allowing for lighting, shading, and special effects
-  **Perspective-Correct Texture Mapping** – Prevents texture distortion across triangles.  
-  **Phong Lighting Model** – Implements ambient, diffuse, and specular shading.  
-  **Depth Buffering / Culling** – Ensures correct visibility and occlusion.  
-  **Camera Controls** – Navigate and view the rendered scene interactively.

---

##  Showcase

| Example Scene | Description |
|----------------|-------------|
| ![Render1](path/to/your_first_gif.gif) | Basic Phong-shaded model |
| ![Render2](path/to/your_second_gif.gif) | Depth culling and texture mapping demo |
| ![Render3](path/to/your_third_gif.gif) | Perspective-corrected textured cube |

---
