# Terrain Rendering

This project is a comprehensive terrain rendering application written in C++ and HLSL, utilizing DirectX 11 for rendering. It showcases many advanced graphics techniques and features, making it a robust demo of terrain visualization and manipulation.

## Features:

### Camera Control: Allows for navigation through the terrain

![playerCam](/images/playerCam.gif)

### Height Maps: Supports height maps for terrain generation, able to create realistic terrain

![height](/images/height.png)

### Texturing: Adds a texture to the height maps to make the map look like terrain

![normals](/images/normals.png)

### Shadows: Adds depth and realism to the scene

![shading](/images/shading.png)

### Skydome: Includes a skydome to simulate the sky, really completes the immersion

![skydome](/images/skydome.png)

### RAW 16-bit Height Maps: Support RAW 16-bit height maps allowing for higher resolution and much more detailed terrain like lower trophs and higher peaks

![RAWheight](/images/RAWheight2.png)

### Terrain Cells and Frustum Culling: Divides the terrain into cells and implements frustum culling, optimizing rendering performance by only drawing visible parts of terrain

![terrainCells](/images/terrainCells.png)
![frustum](/images/frustum.png)
