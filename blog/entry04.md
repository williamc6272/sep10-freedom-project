# Entry 4
##### 12/5/25
## Content 
For this part of my Freedom Project, I chose [A-Frame](https://aframe.io/docs/1.7.0/introduction/), a VR tool that lets me create 3D environments in a web browser. I tinkered with it by adding shapes like boxes, spheres, and cylinders, and I experimented with their positions, sizes, colors, and rotations. I also tried adding simple animations so the objects could spin or move, which made the scene feel more interactive. I included Changing the positions of objects to see how it affected navigation in the scene, Modifying colors and sizes to make objects stand out, Adding an animation component to make the box rotate continuously.

Here’s an example of the code I used to make a spinning box:
``` HTML
<a-box 
  position="-1 0.5 -3" 
  rotation="0 45 0" 
  color="#4CC3D9"
  animation="property: rotation; to: 0 405 0; loop: true; dur: 4000">
</a-box>
```
I will use A-Frame to design a 3D model of nano robots, arranging and animating them to show how they would move and work at crime scenes.

