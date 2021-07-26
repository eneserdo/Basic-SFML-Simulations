# Gravity-Simulation
This project visulizes the Newton's law of universal gravitation via SFML library. Elastic collusion was also implemented for more plausable interactions between the objects.

The purpose of this fun project was to practice object oriented programming methodology using C++ language.

Note that formulas were used directly without any manipulation, so calculation parts are not optimum.

## Menu

Once completed, there will be different setups:

* 2D:
  * 2 moving objects around the [barycenter](https://en.wikipedia.org/wiki/Barycenter).
  * 1 moving object around the still object.
  * Randomly initilized space
  * (TODO) Oversimplified simulation of solar system (using sun, earth and moon such that sun is also orbitting around the center of the Milky Way Galaxy)
* 3D (TODO):


## Features

- Click the left mouse button to create a new object and move around to set its speed. 
- Zoom in/out to specific point (like zooming a map), sliding the view with two finger 
- <kbd>R</kbd> reset the view.
- <kbd>Q</kbd> / <kbd>W</kbd> Change the speed of the simulation.
- <kbd>C</kbd> Use curser as a mass
- <kbd>G</kbd> On/off the gravity.
- <kbd>B</kbd> On/off the boundaries.


## Resources

N-Body simulation requires highly complex approches to model them, actually when N>2 complete solution is not possible. 

To build 3D view, I used camera matrices and quaternions. Quaternions are very fun part of the geometric algebra. Here some links to learn them about:
- [A Swift Introduction to Geometric Algebra](https://youtu.be/60z_hpEAtD8)
- [Let's remove Quaternions from every 3D Engine](https://marctenbosch.com/quaternions/)



