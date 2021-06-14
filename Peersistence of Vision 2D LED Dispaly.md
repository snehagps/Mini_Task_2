# Peersistence of Vision 2D LED Dispaly
## Problem Statement:
The aim of this project is to create a 2 D display using fast rotating LEDs the concept of persistence of vision 

## Ideation and Planning:
We can 3D print the holder  to which we will be fixing our complete assembly.
The Holder should have two parts.
*	The Rotating Part
*	The Stable Part
The rotating arm is the part on which the LEDs will be mounted. This is the part that actually turns, so it should be light, yet sturdy. 
We must calculate the moments of inertia of the system. 
### Motor : 
We have to determine the rotation speed needed to achieve the persistence of vision. This is the first requirement for the motor.
The next requirement is that it should have enough torque. The torque is important, since it will influence the speed at which the rotation arm accelerates; it should come to full speed in a reasonable amount of time.
### Sensor:
We can use either IR sensor or hall sensor to find the time required for one rotation
* Hall Sensor - A Hall effect sensor is a type of sensor which detects the presence and magnitude of a magnetic field using the Hall Effect. We can keep a magnet at one fixed spot closer to the rotating LEDs such that Hall sensor gives a low every time it crosses the spot.
* IR Sensor - An infrared (IR) sensor is an electronic device that measures and detects infrared radiation in its surrounding environment. We can keep a reflecting surface at one fixed spot closer to the rotating LEDs such that IR sensor gives a low every time it crosses the spot.
## Choosing a Pipeline :
Based on the calculated values we should choose a motor which match our requirements. <br />
We can use Neo-pixel LED strips instead of separate LEDs .If we use separate LEDs we would require more input pins so by using LED strip we can reduce the input pin to one <br />
We can use Hall effect sensor instead of IR sensor because IR sensor may reflect from some other white objects in the room .<br />
## Prototyping Phase :
In this phase we assemble all the components and write the code for the micro-controller .
