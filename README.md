# Fuzzy-Mobile-Robot-Control
Mamdani Fuzzy Rule Base has been used to control a robot motion control in an arena. The robot has to meet goals in a sequential order. The motion is tested for 5 scenarios with goals from 1-5 respectively by splitting inputs and outputs into 7 membership functions.
Inputs: Radial Velocity, Angular Velocity, Relative angle between velocity vector and the goal and Distance from the goal
Outputs: Radial Accelration and Angular Acceleration 
Post that, an optimized control is built by reducing the number of membership functions for each input and output.
