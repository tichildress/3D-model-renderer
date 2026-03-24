# OpenGL Rendering Engine (C++)

A modern 3D rendering engine built in C++ using OpenGL. This project demonstrates real-time rendering, model loading, camera controls, and texture handling using industry-relevant libraries.

---

## Overview

This project is a custom-built OpenGL engine designed to render 3D models with lighting, textures, and interactive camera movement. It serves as both a learning project and a foundation for more advanced graphics development.

The engine supports loading GLTF models, applying transformations, and rendering them in a real-time environment.

---

## Features

* OpenGL 3.3 Core Profile rendering
* GLTF model loading and rendering
* Real-time camera movement (WASD + mouse)
* Texture loading using stb_image
* Shader-based lighting system
* Vertex Buffer Objects (VBO), Vertex Array Objects (VAO), and Element Buffer Objects (EBO)
* Depth testing and 3D transformations
* Modular class-based architecture (Model, Mesh, Camera, Shader)

---

## Technologies Used

* C++
* OpenGL
* GLFW (window and input handling)
* GLAD (OpenGL function loading)
* GLM (mathematics library)
* stb_image (image loading)
* nlohmann/json (GLTF parsing)

---

## Controls

| Key        | Action         |
| ---------- | -------------- |
| W          | Move Forward   |
| A          | Move Left      |
| S          | Move Backward  |
| D          | Move Right     |
| Space      | Move Up        |
| Left Ctrl  | Move Down      |
| Mouse      | Look Around    |
| Left Shift | Increase Speed |

---

## Project Structure

```
OpenGlEngine/
│
├── main.cpp
├── Shader/
├── Camera/
├── Model/
├── Mesh/
├── Texture/
│
├── glad.c
├── stb_image.h
│
├── shaders/
│   ├── default.vert
│   ├── default.frag
│
├── models/
│   └── (GLTF models)
```

---

## Setup Instructions

1. Clone the repository:

```
git clone https://github.com/yourusername/your-repo-name.git
```

2. Open the project in Visual Studio

3. Make sure the following dependencies are set up:

   * GLFW
   * GLAD
   * GLM
   * stb_image
   * nlohmann/json

4. Ensure include directories and linker inputs are configured correctly

5. Build and run the project

---

## Example Output

(Add screenshots or GIFs here of your engine rendering models)

---

## Future Improvements

* Lighting enhancements (Phong / PBR)
* Multiple light sources
* Shadow mapping
* UI integration (ImGui)
* Scene editor
* Physics integration

---

## Purpose

This project was created to deepen understanding of:

* Real-time rendering
* Graphics pipelines
* OpenGL architecture
* C++ system design

---

## Author

Tanner Childress
C++ Developer | OpenGL | Web Development

---

## License

This project is open-source and available for learning and personal use.
