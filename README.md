## OpenGl-Desk
Repository created for Module 7, CS-330
# Project Reflection: 3D Desktop Workspace in Modern OpenGL
### Software Design Approach & Process
For this project, my approach began by defining a clean, warm-colored workspace containing a desk, keyboard, monitor, mouse, pen holder, and globe. This workflow helped me hone my skills in spatial breakdown and structural transformation. For example, a pen cup was designed as nested cylinders of varying diameters to create a hollow illusion, while the pencils combined cylinders with cones.

### Program Development & Iteration
My program development strategy relies on incremental progress and trial and error. When rendering the 3D scene, first establish the foundational coordinate system, then render individual objects, and finally apply textures and lighting. I used nested loops to create the keyboard, transforming a single box mesh into a uniform grid of keys. Seeing my code directly translate into a visual, navigable workspace taught me the unique value of immediate visual feedback in debugging.

### Interactive Controls Evolution
I developed interactive camera controls according to the GLFW guide, which required linking mouse and keyboard callbacks. The system advanced from basic horizontal and depth navigation using the WASD keys to full 3D vertical movement along the world Y-axis via the Q and E keys. I also integrated cursor tracking and used the mouse scroll wheel as a variable speed controller to let users speed up or slow down their camera. 

### Academic & Professional Impact
Working with OpenGL, shaders, and matrix mathematics prepares me for advanced coursework in computer vision and parallel computing. Professionally, high-performance, visually-driven development is highly sought after in modern UI/UX architecture and data visualization. Understanding how GPUs process data and compute real-time lighting enables me to write highly optimized, resource-efficient code—making me a much more versatile and capable engineer in the tech industry.
