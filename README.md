# Ray Tracer
![Final render](/progress/sphere18_final_render.png)

## Features

PBR Material types
- Diffuse (Lambertian)
- Metallic
- Dielectric

## Running the Program

1. Create a scene by creating spheres and tweaking camera settings in main.cc  
2. `cmake -B build`  
3. `cmake --build build --config Release ; ./build/Release/raytracer.exe > image.ppm`  
4. Open the image.ppm file in a ppm viewer  

## The Process
![First render](/progress/sphere1.png)  
First render

![Shading with surface normals](/progress/sphere3.png)  
Shading with surface normals

![Antialiasing](/progress/sphere4_antialiased.png)  
Antialiasing

![Diffuse material](/progress/sphere5.png)  
Diffuse material

![Shadow acne removed](/progress/sphere7.png)  
Shadow acne removed

![Lambertian reflection](/progress/sphere8_lambertian.png)  
Lambertian reflection

![Gamma correction](/progress/sphere9_gamma_corrected.png)  
Gamma correction

![Metallic material](/progress/sphere10_metallic.png)  
Metallic material

![Metallic material with fuzz](/progress/sphere11_fuzzy_metal.png)  
Metallic material with fuzziness

![Dielectric (glass) material](/progress/sphere12_dielectric.png)  
Dielectric (glass) material

![Hollow glass sphere using Schlick's approximation](/progress/sphere14_schlick.png)  
Hollow glass sphere using Schlick's approximation

![Camera position far away](/progress/sphere16_camera_positioning.png)  
Camera position far away

![A close-up shot](/progress/sphere16_camera_positioning_2.png)  
A close-up shot

![Depth of field added](/progress/sphere17_depth_of_field.png)  
Depth of field added

![Final render](/progress/sphere18_final_render.png)  
Final render with all features


## Guide by Peter Shirley:  
https://raytracing.github.io/books/RayTracingInOneWeekend.html
