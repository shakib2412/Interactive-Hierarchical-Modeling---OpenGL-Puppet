# Interactive Hierarchical Modeling - OpenGL Puppet

## Project Overview
This project is an academic endeavor created for the Introduction to Computer Graphics course. It involves constructing a 3D animated puppet through hierarchical modeling using OpenGL and the C++ programming language. The puppet is controlled interactively via keyboard inputs, featuring detailed arm, leg, and torso movements, as well as advanced lighting and texture implementation.

## Features
- **Hierarchical Modeling**: Build a complex 3D puppet using simple geometric primitives arranged in a hierarchical structure.
- **Interactive Controls**: Manipulate the puppet's movements through comprehensive keyboard controls.
- **Custom Animations**: Includes animations like walking, which can be toggled on and off.
- **Dynamic Lighting and Textures**: Utilize OpenGL's lighting and material functionalities to enhance the visual appearance of the puppet.
- **User Guide**: Detailed control guidelines for operating the puppet within the simulation.

## Installation
1. **Prerequisites**:
   - Ensure OpenGL and GLUT are installed on your system. These are necessary for compiling and running the project.
2. **Clone the Repository**:
   
   git clone https://github.com/shakib2412/Interactive-Hierarchical-Modeling---OpenGL-Puppet.git
  
3. **Compile the Project**:
   - Navigate to the project directory:
     
     cd Interactive-Hierarchical-Modeling---OpenGL-Puppet
   
   - Compile using g++ or any compatible C++ compiler that supports OpenGL:
     
     g++ -o puppet Puppet.cpp -lGL -lGLU -lglut
    
4. **Run the Program**:
   
   ./puppet


## Usage
Control the puppet using the following keyboard commands:

### Movement Controls
- **Arms**
  - 'q', 'a': Rotate right shoulder.
  - 'w', 's': Rotate left shoulder.
  - 'z', 'x': Extend/retract right arm.
  - 'Z', 'X': Extend/retract left arm.

### Leg Controls
- 'y', 'u': Raise/lower right leg.
- 'h', 'j': Raise/lower left leg.
- 'Y', 'U': Move right leg outward/inward.
- 'H', 'J': Move left leg outward/inward.

### Torso Controls
- 'd', 'g': Rotate torso right/left.
- 'r', 'f': Tilt torso forward/backward.

### Additional Functions
- **View Rotation**: Use the arrow keys to rotate the view.
- **Lighting Controls**:
  - 'p', 'i': Rotate light source right/left.
  - 'o', '9': Move light source forward/backward.
- **Miscellaneous**:
  - 'Page Up': Fire cannon.
  - '1': Start walking animation.
  - '2': Stop walking animation.
  - '3': Toggle between wireframe and solid view.
  - '4': Exit the program.

## Contributing
Contributions are welcome! If you have suggestions for improving the project or adding new features, please feel free to fork the repository, make your changes, and submit a pull request.
