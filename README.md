# GLGame (A Tiny OpenGL based C++ Game Engine)

![GLGame Logo](https://github.com/swr06/GLGame/blob/master/Branding/Logo1.PNG)
<p align=center>
Created by Samuel Rasquinha using C++17 and OpenGL 3.3 :game_die:
</p>

# Objective 

GLGame was created to be as simple and straightforward as possible. Each part of the engine requires little to no understanding of OpenGL and other computer graphic concepts.

It uses simple type names and has simple arguments such as ``Object``, ``Entity``, ``Sprite``.

# Features

A Tiny 2D OpenGL based C++ Game Engine that is fast, lightweight and comes with a level editor and the below features :
- Abstract OpenGL (To write custom code) ✓
- Camera Culling ✓
- Sprite Batching ✓
- Light Batching ✓
- Animations ✓
  - Custom animation speed ✓
 - Scene Editor (W.I.P)
- Transformations ✓
- Logger ✓
- Audio 
- Post Processing (W.I.P)
- Lighting ✓
- Particles
- Physics
- Helper functions (such as windowing functions etc..)

This engine is still highly in development.

# Features to come

I would like to implement the following features in the coming years :
- Multithreading
- Networking
- Save game
- More helper functions
- Custom GUI Library

# Compiling

To compile this project, you will need Microsoft Visual Studio 2019 and the VSC++ compiler (which supports C++17).
Open the ``.sln`` file using Visual Studio and select the x86 (or Win32) configuration. 
You can compile it in both modes (Debug or Release) with the x86 (Win32) configuration.

# About the Scene Editor 

The scene editor has to be run during runtime.
Just call the ``SceneEditor::LaunchSceneEditor()`` function and it will launch the Scene Editor with all the objects you have or will create.

# Dependencies 

GLGame has very humble dependencies.

- ``C++17`` (for ``std::filesystem``)
- ``stb_image`` (for reading texture files)
- ``ImGui`` (Bloat free immediate mode GUI interface by Omar Ocurnut)
- ``GLEW`` (OpenGL wrangler library)
- ``GLFW`` (Windowing environment)

# About the Author

My name is Samuel Rasquinha (samuelrasquinha@gmail.com) and I am a 14 year old programmer from India. 

# Development Specs

- Processor : AMD Ryzen 3 2200g
- Graphics  : Integrated Vega 8 graphics
- Ram       : 8.0 GB
- MB        : AsRock A320M MB

This engine managed to get 300+ FPS in the game with the scene editor running.

# Contact Me : 

- Discord : @swr06 #1899 
- Gmail   : ``samuelrasquinha@gmail.com``
- Instagram : Samuel Rasquinha

# Supporting this project

If you like this project and would like to support it, please do star it on GitHub.
