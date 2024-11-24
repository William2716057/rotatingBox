# rotatingCube

A simple 3D rotating box created using HTML and CSS. This simple script will display a rotating blue box on screen and the code can be adapted to the needs of the user.

![rotatingBox](https://github.com/user-attachments/assets/20b650a9-6cf5-4006-835f-48445899b751)

## Files
This repository contains the following files:

- index.html: The HTML structure that defines the 3D box.
- style.css: The CSS styles that handle the 3D transformations, animations, and styling of the box.

## How It Works
HTML (index.html)
The HTML defines a container div with a wrapper div inside it. The wrapper contains six div elements representing the faces of the box (front, back, left, right, top, bottom). Each of these faces is styled and positioned to create the 3D effect.


1. The .container class sets a perspective of 800px, which is essential for the 3D effect.
2. The .wrapper class applies transform-style: preserve-3d to enable 3D transformations and infinite rotation to display spinning effect.
Each .face is a 2D square, but with different 3D transformations applied (using rotateX and rotateY), they are positioned to form a cube.
The @keyframes rule animates the rotation of the box around both the X and Y axes.

## Setup

1. Clone or download this repository.
```
git clone https://github.com/William2716057/rotatingBox.git
```
2. Open the index.html file in any modern web browser.

### Customization
- You can adjust the size of the box by changing the width and height of the .wrapper in the CSS.
- The speed of the rotation can be modified by changing the duration of the animation property in .wrapper.
- To change the color of the faces, modify the background-color property for each .face in style.css.
