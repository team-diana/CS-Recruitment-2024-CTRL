# [Across The Universe](https://www.youtube.com/watch?v=NLddD6Xf-8g)

One essential feature of every rover, is the ability to traverse terrain. Indeed, this is the essential element distinguishing a rover from a probe or from a dishwasher for that matter. The more the rover is able to navigate autonomously, the better. 

## Instructions 
We need you to design a navigation system for a rover so that it can explore an area currently being investigated. 
The rover is equipped with pose estimation sensors, and the distance between the front and rear axes of the vehicle is 1.5m. 
A control system still needs to be developed . 

We are asking your help to:
- simulate the output of the pose estimation sensors.
- write a realistic plausible model for the rover
- implement a control algorithm that allows the rover to reach a target position indicated as a couple of coordinates X and Y (or if you prefer an area of a certain size around that given coordinates) completely autonomously. The algorithm must take into account the rover's current pose given by the sensors
- some interface that shows the rover's pose and its path to the target

The rover's command variables are subject to saturation:
- the maximum speed is worth in the form of 10m/s
- maximum steering angle holds in modulus 35°
The rover can be considered as arrived at the destination if its distance to the target is less than or equal to 30cm.

You can ignore the Z axis for this challenge and assume that the rover is always on a flat surface.

## Expected deliverables
- Provide Matlab file(s) and Simulink model(s) of your solution
If you prefer to use another programming language, please provide the necessary files to run your solution.

## Challenge's score
Total score: 600