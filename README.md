---

## Still In Progress ##
---

# Basic Game Engine Learning Project

A beginner-friendly game engine project built using C++ to understand how real game engines work internally.  
This project focuses on learning core engine architecture, rendering flow, memory handling, input systems, and engine structure from scratch.

---

# Goals

The purpose of this project is to:

- Learn modern C++
- Understand engine architecture
- Learn how rendering pipelines work
- Build systems step-by-step instead of using existing engines
- Understand memory management and performance optimization
- Gain low-level programming knowledge useful for game development

---

# Features (Planned)

## Core Systems
- Window creation
- Main engine loop
- Delta time system
- Input handling
- Logging system
- Event system

## Rendering
- OpenGL renderer
- Clear screen rendering
- Shader system
- Texture loading
- 2D rendering
- Camera system

## Engine Architecture
- ECS (Entity Component System)
- Scene management
- Resource manager
- Asset loading system

## Debugging Tools
- FPS counter
- Debug console
- Profiling tools

---

# Tech Stack

- Language: C++
- Build System: CMake
- Graphics API: OpenGL
- Windowing: GLFW
- OpenGL Loader: GLAD
- IDE: Visual Studio

---

# Project Structure

```txt
BasicEngine/
│
├── Engine/
│   ├── Core/
│   ├── Renderer/
│   ├── Input/
│   ├── Math/
│   └── Utils/
│
├── Sandbox/
│   └── Main.cpp
│
├── Vendor/
│
├── CMakeLists.txt
└── README.md
