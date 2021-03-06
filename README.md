## Computer Graphics and Visualization Lab (VTU)

### Index
 1. [3D Sierpinski](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/1.c)    
 2. [Liang-Barsky](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/2.c)    
 3. [Color Cube with OpenGLTransformation](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/3.c)
 4. [House](https://github.com/SubhrajyotiSen/10CSL67/raw/master/4.c)
 5. [Cohen-Sutherland](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/5.c)    
 6. [Cylinder and Parallelepiped](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/6.c)     
 7. [Tea pot](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/7.c)
 8. [Color cube with perspective viewing](https://github.com/SubhrajyotiSen/10CSL67/raw/master/8.c)
 9. [Polygon using scan-line area filling](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/9.c)
 10. [Rectangular mesh](https://raw.githubusercontent.com/SubhrajyotiSen/10CSL67/master/10.c)      
 

----------


### Installing on Linux
You can install the required dependencies using the following commands

#### On Debian based systems
    sudo apt-get update
    sudo apt-get install freeglut3
    sudo apt-get install freeglut3-dev
    sudo apt-get install binutils-gold
    sudo apt-get install g++ cmake
    sudo apt-get install libglew-dev
    sudo apt-get install g++
    sudo apt-get install mesa-common-dev
    sudo apt-get install build-essential
    sudo apt-get install libglew1.5-dev libglm-dev
        
#### On Fedora/RedHat based systems
    sudo dnf group install c-development
    sudo dnf install freeglut-devel
    
#### On Arch based systems
    pacman -S mesa glu freeglut
    
#### On MacOS/OSX
     add OPENGL.framework and GLUT.framework to project properties in XCode
    
### Compiling the code
    sh compile.sh file
    
### Executing the  code
    ./file.o
