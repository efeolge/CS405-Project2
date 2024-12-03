# Computer Graphics Project 2

## Overview
This project implements texture handling and lighting systems in WebGL.

## Implementation Details

### Task 1: Texture Handling Implementation
#### Features
* Support for non-power-of-2 sized images
* Multiple image format compatibility (JPEG, PNG)
* Enhanced texture parameter handling
* Proper texture wrapping and filtering

#### Technical Details
* ```CLAMP_TO_EDGE``` wrapping implementation
* ```LINEAR``` filtering for both minification and magnification
* Efficient texture memory management
* Tested successfully with provided test images (leaves.jpg)

### Task 2: Lighting System Implementation
#### Core Components
* Ambient lighting
* Diffuse lighting
* Specular lighting
* Dynamic light positioning

#### Key Features
* Real-time light control using arrow keys
* Adjustable lighting parameters via UI
* Shader-based lighting calculations
* Integrated texture and lighting systems

#### Controls
* Arrow Keys: Move light position
* UI Sliders:
  * Ambient Light Density
  * Specular Light Intensity
* Toggles:
  * Enable Light
  * Show Texture

## Testing
All features have been thoroughly tested with:
* Various 3D models
* Different texture types
* Multiple lighting configurations

## Usage
1. Load a 3D model (.obj file)
2. Apply texture (supports both power-of-2 and non-power-of-2 images)
3. Enable lighting
4. Adjust lighting parameters as needed
5. Use arrow keys to position the light source

---
*Project completed as part of Computer Graphics course*
