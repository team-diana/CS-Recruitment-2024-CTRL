# [Collide](https://www.youtube.com/watch?v=ca9ub9rpNK4)

Mechanics people usually hate two things: CS people touching the rover and the rover colliding with obstacles at any given speed. For the first problem they usually prevent or cure by employing wise doses of hammers applied at precise locations. For the second problem they have to instead resort to the same CS people they previously hurt.

DIANA's rovers are equipped with a Time-of-Flight (TOF) sensor that can detect the presence of obstacles in front of the rover. The sensor provides distance measurements between the rover and the obstacle.

We ask you to use a TOF sensor on the rover to detect the presence of boxes (obstacles) and generate an alert signal as output using Simulink.
For sake of semplicity we assume to move on a X,Y plane, starting from position (0,0).

## Instructions:

1. **Distance detection with TOF**:  
   Use the TOF sensor to measure the distance between the rover and the obstacle (box).
   - If the sensor detects a distance between 10 cm and 100 cm, the system should generate an alert (for example, an output signal with a value of 1 to indicate the presence of a box).
   - If the distance is less than 10 cm or greater than 100 cm, the output should indicate that no obstacle is present (for example, an output signal with a value of 0).

2. **Handling sensor disconnection**:  
   If the sensor does not provide any measurement (e.g., in case of disconnection), the system should generate an error alert (for example, an output signal with a negative value or a predefined value to indicate a malfunction).

3. **Modeling in Simulink**:  
   Build a Simulink model that simulates the behavior of the TOF sensor and the alert signal output (1 = obstacle detected, 0 = no obstacle).
   Display the output signal in Simulink based on the distance detected by the sensor.

## Expected deliverables:

- A Simulink file that models the sensor’s behavior and clearly shows the alert signal generated when the presence of a box is detected.

## Challenge's score
Total score: 400