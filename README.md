# Wireframe-3D-Graphics-Viewer-Lighting-Practice
A 3D wireframe and polygon graphics engine built using Python, NumPy, and Pygame. This project demonstrates 3D coordinate transformations, projections, and the Phong Lighting Model (Ambient, Diffuse, and Specular reflection) applied to custom 3D shapes like spheroids and fractal landscapes.
Features

Polygon Shading: Renders filled 3D polygons using calculated surface normals.

Phong Lighting Model: Simulates realistic lighting via ambient light, diffuse scattering, and specular highlights (gloss).

Dynamic Light Navigation: Rotate the light source position in real-time around the scene using keyboard controls.

Geometric Primitives: Built-in generators for cuboids, spheroids (beach balls), horizontal grids, and fractal landscapes.

Project Structure

wireframe.py: Core 3D engine containing vector math, transformation matrices (translate, scale, rotateX/Y/Z), and the Wireframe / WireframeGroup classes.

basicShapes.py: Procedural generator functions for 3D primitives like cuboids, spheroids, and fractal terrains.

phongpython.py (Main Script): Initializes the Pygame display window, sets up the 3D scene, manages key events, and handles the Phong lighting rendering loop.

Requirements

Python 3.x

NumPy

Pygame (or Pygame-CE)

Installation & Running

Ensure all project files (phongpython.py, wireframe.py, and basicShapes.py) are saved in the same directory.

Install the required dependencies via your terminal:

pip install pygame-ce numpy


Run the main script:

python phongpython.py


Controls

While the visualization window is active, use the following keys to orbit the light source around the object:

W / S: Rotate light source Up / Down (X-axis)

A / D: Rotate light source Left / Right (Y-axis)

Q / E: Rotate light source Counterclockwise / Clockwise (Z-axis)
