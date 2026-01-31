# Learn-OpenGL

A repository documenting progress through the LearnOpenGL curriculum.

## Technical Stack
* Language: C++17 / C++20
* Graphics API: OpenGL 3.3 (Core Profile)
* Window Management: GLFW
* Function Loading: GLAD

## Project Structure
The project is organized by chapter to maintain modularity:
* 01_Getting_Started/: Contains source files for window creation and coordinate systems.
* include/: Header files for GLFW and GLAD.
* glad.c: OpenGL function loader implementation.

## Progress
- [x] Chapter 1: Hello Window
- [x] Chapter 2: Hello Triangle
- [ ] Chapter 3: Shaders
- [ ] Chapter 4: Textures
- [ ] Chapter 5: Transformations

## Build Instructions
To compile the current source using MinGW: g++ 01_Getting_Started/ 02_Hello_Triangle.cpp glad.c -o app.exe -linclude -Lib -lglfw3 -lopengl32 -lgdi32

## Build Instructions
To compile the current source using MinGW:
g++ 01_Getting_Started/02_Hello_Triangle.cpp glad.c -o app.exe -Iinclude -Llib -lglfw3 -lopengl32 -lgdi32
