# OpenGL-Space-Adventure
CS 550 Final project

## Introduction

In the project, the program build a scene about a spaceship traveling in space. The
background is an unknown place in the universe. Therefore, some physical theories are
the same as the solar system, but some of them are not.

For example, the motion of planets follows Kepler's Third law as the solar system, but
the size, and the amount of planets are different. The mission is to rescue the other
missing spaceship in this place.

## Implement

There are totally five different planets and a star. As we mentioned above, the planet
follows Kepler’s law. In addition, I add some small dust in the universe to make the
scene more abundant.

For the two spaceships in space, which load from the obj file, one is immovable, the
other one can be controlled by users. On the left-top of the screen, there is a
count-down timer. To complete the mission, not only find the ship, but also close to it.
The distance should be less than one between the mission ship and broken ship. If we
could not find the broken spaceship in time, the scene will show the mission failed.
There are two view options for users, one is inside the spaceship, the other is outside
the spaceship. If you are inside the spaceship, key = ‘w’, ’a’, ‘s’, ‘d’ (up, left, down, right)
can change the direction we are looking, key = ‘n’, ‘m’ for forward and backward. In the
outside mode, we can use the mouse to zoom in/out as usual.

Note: more detail in report

## Prerequisites

 install Visual studio and OpenGL would be fine.
  
## ScreenShot

![1](https://github.com/tony85212/OpenGL-Space-Adventure/blob/main/screenshot1.png)
![2](https://github.com/tony85212/OpenGL-Space-Adventure/blob/main/screenshot2.png)
