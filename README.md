# PBET: Augmented Reality Rendering

## Overview
This project demonstrates **photorealistic augmented reality compositing** by integrating computer-generated 3D objects into real-world photographs. The goal is to ensure **realistic lighting, reflections, and shadows** using **physically based rendering (PBR)**. This work was developed as part of the **Computer Graphics (Spring 2023)** coursework.

To achieve high-quality results, we used:
- **PBRT v3** – A physically based rendering engine.
- **Blender** – For 3D modeling and scene reconstruction.
- **Luminance HDR** – For tone mapping and exposure correction.
- **GIMP** – For image compositing and post-processing.

## Key Features
### Scene Setup & Image Capture
- **Designed a real-world scene** with complex reflections and textures.
- **Captured a reference photograph** with accurate lighting conditions.
- **Collected texture images** to enhance material realism.
![image](https://github.com/user-attachments/assets/0ec9076c-090f-414d-b65f-1ee2bf57786e)

### 3D Modeling & Rendering
- **Reconstructed real-world objects** as proxy models in Blender.
- **Matched virtual camera settings** to align with real-world perspective.
- **Applied realistic materials** (metal, glass, plastic) for accurate reflections.
- **Rendered using PBRT** to generate physically accurate synthetic images.
![image](https://github.com/user-attachments/assets/93da76e7-7aaa-40f8-b7bc-eb995a4179b4)

### Compositing & Post-Processing
- **Blended the rendered object** seamlessly into the real photograph.
- **Adjusted lighting, shadows, and reflections** for photorealistic integration.
- **Enhanced realism** using HDR tone mapping and fine-tuned color correction.
![image](https://github.com/user-attachments/assets/c0b51dd9-cc84-44c6-a630-ac917dcd00cd)

## Implementation Workflow
1. **Scene Planning** – Selected objects with reflective and textured surfaces.
2. **3D Modeling & Texturing** – Built proxy models and applied realistic materials.
3. **Rendering with PBRT** – Configured lighting, cameras, and shading.
4. **Compositing & Refinement** – Merged the rendered object into the real-world photo.

## Results & Visual Effects Achieved
- **Reflections of real-world objects** on synthetic materials.
- **Shadows cast by real objects onto virtual objects** and vice versa.
- **Accurate occlusions** where real and synthetic elements overlap.
- **Metallic and glass materials** exhibiting realistic light interactions.
![1-1 output view](https://github.com/user-attachments/assets/74178bab-a8d1-4279-8c7b-196f3da685af)

## Challenges & Future Improvements
- **Reducing rendering noise** in complex materials like glass.
- **Enhancing shadow blending** for better integration with real scenes.
- **Improving environmental reflections** to match surrounding elements.

## Future Enhancements
- **Advanced lighting models**: Experimenting with HDR environment maps.
- **Higher-resolution textures** for improved material accuracy.
- **Automated post-processing** for seamless compositing.

## Acknowledgments
Developed for **Computer Graphics (Spring 2023)** using **PBRT, Blender, and GIMP**.

## References
- [PBRT: Physically Based Rendering](https://pbrt.org/)
- [Blender 3D Creation Suite](https://www.blender.org/)
- [Luminance HDR](http://qtpfsgui.sourceforge.net/)
