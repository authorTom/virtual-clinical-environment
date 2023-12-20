# Virtual Clinical Environment Project
<a href="https://github.com/UHBinnovate?tab=followers">
         <img alt="followers" title="Follow me on Github for Updates" src="https://custom-icon-badges.demolab.com/github/followers/authorTom?color=236ad3&labelColor=1155ba&style=for-the-badge&logo=person-add&label=Follow&logoColor=white"/></a> 

![Maintenance](https://img.shields.io/maintenance/yes/2023?style=for-the-badge)
![Last-Commit](https://img.shields.io/github/last-commit/authorTom/virtual-clinical-environment?style=for-the-badge)
## Objectives
* To design and develop a realistic virtual clinical environment that extends beyond the capabilities of 360 videos and images, granting users 6 degrees of freedom (6DoF) to explore and engage with the content. <br />
* To compare several environment development techniques such as photogrammetry, NeRFs, and Gaussian splatting. <br /> 
## Key Features 
1. **Realistic Virtual Environment** <br />
   Create a realistic simulation of a clinical setting where staff and students can practice and learn. <br />
3. **6DoF Navigation** <br />
   Unlike traditional 360-degree videos or images, users will be able to move freely in any direction—forward/backward, up/down, left/right, pitch, yaw, and roll. <br /> 
5. **XR Headmounted Display Compatibility** <br />
   Ensure that the environment is optimised for and compatible with various standalone XR head mounted displays for immersive experiences. <br />
## Project Scope 
The project will involve the following steps: 
1. **Data collection**: Capture video and image data of a clinical environment using a suitable camera system. <br />
2. **3D reconstruction**: Use photogrammetry, NeRFs and Gaussian Splatting to construct individual 3D models of the clinical environment from the captured image data. <br />
3. **XR integration**: Integrate the captured virtual environments with a commercially available game engine (Unreal Engine). Then implement an XR head mounted display to allow users to interact with 6DoF. <br />
4. **Comparative analysis**: Compare the 3D virtual environments for the following. <br />
   1. **Resolution**: and Detail: Compare the detail level and resolution across the three techniques, ensuring the most realistic representation of the clinical environment. <br />
   2. **Performance**: Assess the real-time rendering performance of each technique, especially when used on the XR head mounted displays. <br />
   3. **Flexibility**: Evaluate the ability of each technique to allow changes or updates to the environment. <br />
   4. **Development time & cost**: Analyse the time and resources required to develop the environment using each technique. <br /> 
6. **Evaluation**: Evaluate the usability and effectiveness of the virtual environments within a clinical educational context. <br />
## Potential benefits 
* **Enhanced training**: Clinical staff and students can immerse themselves in cost effective realistic scenarios, improving the quality of training and education. <br />
* **Safe learning**: Allows students and staff to practice without real-world consequences. <br />
* **Accessibility**: Can be accessed anytime, anywhere, offering flexibility in learning and training. <br />
## Techniques for Development 
### Photogrammetry
Photogrammetry is the science and technology of obtaining reliable information about physical objects and the environment through the process of recording, measuring and interpreting photographic images and patterns of electromagnetic radiant imagery and other phenomena. <br />
<br />
It is a non-contact method of 3D measurement that uses multiple images of an object to reconstruct its 3D shape and position. Photogrammetry is used in a wide variety of applications, including surveying, mapping, engineering, archaeology, and special effects. <br />
<br />
Photogrammetry can be performed using a variety of equipment, including traditional cameras, drones, and satellite scanners. The type of equipment used depends on the specific application. <br />
<br />
To perform photogrammetry, a series of images of the object or scene of interest are taken from different angles. The images are then processed using software to create a 3D model. The software matches points in the different images to create a point cloud. The point cloud is then used to generate a mesh, which is a surface that represents the 3D shape of the object or scene. <br />
### NeRFs (Neural Radiance Fields)
NeRF stands for Neural Radiance Fields. It is a machine learning approach to 3D reconstruction and rendering. NeRFs represent a 3D scene as a neural network that predicts the colour and density of light at any point in the scene. <br />
<br />
To train a NeRF, a set of images of the scene are taken from different angles. The NeRF is then trained to predict the colour and density of light at each pixel in each image. Once the NeRF is trained, it can be used to render the scene from any viewpoint. <br />
<br />
NeRFs have several advantages over traditional 3D rendering techniques. First, they are very efficient, as they can be implemented using standard GPU rasterization hardware. Second, they are very flexible, as they can represent a wide variety of 3D scenes, including those with complex geometries and materials. Third, they are very scalable, as they can be used to render scenes with millions of polygons. <br />
<br />
NeRFs have been used to create a variety of applications, including real-time rendering of 3D scenes, 3D reconstruction from images, and 3D printing. <br />
<br />
[📄 NeRF: Neural Radiance Fields (matthewtancik.com)](https://www.matthewtancik.com/nerf)
### Gaussian Splatting
Gaussian splatting is a rasterization technique for 3D reconstruction and rendering. It represents a 3D scene as millions of particles, each of which is a 3D Gaussian function. Each particle has a position, rotation, scale, opacity, and view-dependent colour. <br /> 
<br />
To render a Gaussian splatting scene, the particles are first converted into 2D space ("splatted") and then organized and sorted for efficient rendering. The splatting process involves projecting each particle onto the image plane and then blending it with the existing pixels. The opacity and view-dependent colour of the particle determine how much it contributes to the final colour of the pixel. <br /> 
<br />
Gaussian splatting has several advantages over traditional 3D rendering techniques. First, it is very efficient, as it can be implemented using standard GPU rasterization hardware. Second, it is very flexible, as it can represent a wide variety of 3D scenes, including those with complex geometries and materials. Third, it is very scalable, as it can be used to render scenes with millions of polygons. <br /> 
<br />
Gaussian splatting has been used to create a variety of applications, including real-time rendering of 3D scenes, 3D reconstruction from images, and 3D printing. It is a powerful technique that has the potential to revolutionise the way we interact with 3D content. <br />
<br />
[📄 3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/)
## Comparison of Techniques 
Photogrammetry is a well-established technique for 3D reconstruction, but it can be time-consuming and requires a large amount of data. NeRFs is a newer technique that is less data-intensive, but it can be more difficult to train and deploy. Gaussian splatting is a rendering technique that is well-suited for XR applications, as it is efficient and scalable. <br />
<br />
For this project, we will compare the performance of photogrammetry, NeRFs and Gaussian splatting for reconstructing a clinical environment. We will also evaluate the usability and effectiveness of rendering the virtual environment in XR using Unreal Engine. <br /> 
## Data Collection
[What are the Best Camera Settings to take a NeRF?](https://radiancefields.com/what-are-the-best-camera-settings-to-take-a-nerf/)
[What’s the best Focal Length to take a NeRF?](https://radiancefields.com/whats-the-best-focal-length-to-take-a-nerf/)
## 3D Reconstruction
## XR Integration
## Tools & Resources
[🔨XVERSE: A free Unreal Engine 5 Gaussian Splatting plugin](https://github.com/xverse-engine/XV3DGS-UEPlugin/releases) <br /> 
[🔨 Gauzilla: A 3D Gaussian Splatting (3DGS) renderer written in Rust for platform-agnostic WebAssembly (WASM)](https://github.com/BladeTransformerLLC/gauzilla) <br /> 
[🔨 4D Gaussian Splatting for Real-Time Dynamic Scene Rendering](https://guanjunwu.github.io/4dgs/) <br /> 
[📺 Getting Started With 3D Gaussian Splatting for Windows: (Beginner Tutorial)](https://www.youtube.com/watch?v=UXtuigy_wYc) <br /> 
[📄 Getting Started With 3D Gaussian Splatting for Windows: gaussian-splatting-Windows GitHub repository](https://github.com/jonstephens85/gaussian-splatting-Windows) <br /> 
[🔨 Akiya Research Institute 3D Gaussians Plugin for UE5](https://www.unrealengine.com/marketplace/ja/product/410c8105b3aa41d38ab68660295bd7f3?sessionInvalidated=true) <br /> 
[🔨 TurboNeRF](https://github.com/JamesPerlman/TurboNeRF) <br /> 
[🔨 nerfstudio](https://github.com/nerfstudio-project/nerfstudio) <br /> 
## Comparative Analysis
## Evaluation

