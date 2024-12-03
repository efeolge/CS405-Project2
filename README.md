# CS405-Project2

Computer Graphics Project 2 - Texture and Lighting Implementation
Task 1: Texture Handling
In this task, I implemented texture handling for non-power-of-2 sized images in WebGL. The main implementation was done in the setTexture method:

Added proper texture parameter handling for both power-of-2 and non-power-of-2 textures
Used CLAMP_TO_EDGE for texture wrapping to prevent artifacts
Implemented appropriate texture filtering using LINEAR for both minification and magnification
Supported loading of both JPEG and PNG image formats
Successfully tested with the provided leaves.jpg image

Task 2: Lighting Implementation
For the lighting system, I implemented:

Added lighting uniforms in the constructor:

Light position
Enable/disable lighting
Ambient light intensity
Specular light intensity


Modified vertex and fragment shaders to handle:

Ambient lighting
Diffuse lighting
Specular lighting effects


Implemented lighting control functions:

enableLighting(): Toggles lighting on/off
setAmbientLight(): Controls ambient light intensity
setSpecularLight(): Adjusts specular highlights



The lighting system allows for dynamic light position control using arrow keys and adjustable lighting parameters through the UI sliders.
Testing

The implementation was tested using various 3D models
Light position can be controlled using arrow keys
Light intensities can be adjusted using the UI sliders
Both textured and lit rendering work as expected
