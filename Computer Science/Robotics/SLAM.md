**SImultaneous Localization and Mapping (SLAM)** is a set of algorithms, or a system in [Robotics], which takes sensor data (most importantly visual) as an input, and creates a digital representation of the real space, while simultaneously estimating the agent's position in the given space.

A useful algorithm for SLAM is [[ICP]]. In order to synchronize and merge multiple types of sensors together (such as a [[ToF]] camera and an [[IMU]] sensor), a [[Sensor Fusion]] algorithm is needed.

The greatest challenge with SLAM is dealing with the inaccuracy of the sensors. There is always some degree of error in every sensor, and if the SLAM system does not account for this and correct, the error will grow over time and the algorithm will yield increasingly inaccurate results.

In a lot of applications, there is a manual input of some sort of information (a previously created map of the space the agent will move in, the starting position, or the whole route of the agent is precalculated, so that the system is always on the same track).