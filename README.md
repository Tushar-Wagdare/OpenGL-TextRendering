# OpenGL Text Rendering with FreeType

This repository demonstrates how to render text using OpenGL with the help of the FreeType library. It provides a practical implementation for displaying text in your OpenGL applications, including handling different font types and sizes.

## Overview

This project focuses on:

*   **Text Rendering:**  Demonstrates how to load font data using FreeType, generate texture atlases, and render characters on the screen in OpenGL.
*   **Font Management:** Provides the tools to manage different font files and settings within your OpenGL application.

## Folder Structure

The repository is organized as follows:

*   **`TextRendering/x64/Debug`:**  Debug build output directory for the Text Rendering example.
*   **`resources`**: Contains the necessary resources such as fonts and shaders.
*   **`shaders`**:  Contains shader source files used for rendering the text.
*   **`x64/Debug`:**  General debug build output directory.
*   `.gitignore`: File for excluding untracked files in git.
*   `Logger.h`: Header file for a simple logger class
*   `MyIcon.ico`: Icon file.
*   `OGL.cpp`:  Main source file of the OpenGL application.
*   `OGL.rc`: Resource script file for windows.
*    `OGL.sln`: Visual studio solution file.
*   `OGLvcxpj`: Visual studio project file.
*   `OGLvcxpj.filters`:  Filter for the Visual Studio project
*   `Resource.h`: Header file for resources.
*   `Screenshot 2025-01-31 163515.png`: Sample Screenshot.
*   `Shader.h`: Header file for handling shaders
*   `Timer.h`: Header file for a simple timer.
*   `WindowManager.cpp`: Cpp file for managing the window
*   `WindowManager.h`: Header file for the window manager.
*  `camera.h`: Header file for camera class
*  `mesh.h`: Header file for mesh class
*   `model.h`: Header file for the model class
*  `targetver.h`: Header file for the target windows version.

## How to Use

1.  **Clone:** Clone this repository to your local machine.
2.  **Dependencies:** Ensure you have OpenGL and a C++ compiler setup. You will also need FreeType library installed. You may also need libraries like GLFW (for window creation) and GLEW (for OpenGL extensions).
3.  **Build:** Use the Visual Studio project (OGL.sln) included, or any similar build environment to compile your project
4. ** Run:** Execute the compiled project.
5.  **Explore and modify:** Feel free to modify the code, experiment with different font settings, or integrate text rendering into your own OpenGL project.

## Compilation Instructions (General)

You can compile the project in your respective environments. The project is set up for Windows. The following are general compiling instructions for this project.

*   **Windows:**
     * Use the included solution file `OGL.sln` with Visual Studio.
     * Alternatively, use other tools like CMake to create build files.
*   **Other Platforms:**
     *   You'll need to install FreeType library and configure your build system accordingly (e.g., use CMake).
     *   You may also need to link GLFW, GLEW or other equivalent libraries for your platform.

## Contribution Guidelines

Contributions are welcome! If you have improvements, bug fixes, or want to add a new feature, please follow these steps:

1.  **Fork:** Fork the repository to your GitHub account.
2.  **Create Branch:** Create a new branch for your feature or fix (e.g., `git checkout -b my-new-feature`).
3.  **Implement:** Make your changes, ensuring the code is well-documented.
4.  **Test:** Include necessary tests where applicable.
5.  **Commit:** Commit your changes with a descriptive commit message (e.g., `git commit -m "Add: Improved font loading performance"`).
6.  **Push:** Push your changes to your branch (`git push origin my-new-feature`).
7.  **Pull Request:** Create a pull request to merge your changes into the main branch.

## Code Style

Please make sure that your code is well-formatted, well-commented, and follows a consistent coding style, preferably adhering to common C++ coding guidelines.

## License

This project is licensed under the [Choose your license, e.g., MIT License]. See the `LICENSE` file for more details.

## Contact

If you have any questions or suggestions, feel free to open an issue or contact me directly.

## TODO (Future Improvements)

*   Add support for different font styles (e.g., bold, italic).
*   Include multi-line text rendering and word wrapping.
*   Implement more advanced text effects.
*   Add a more flexible resource management.
