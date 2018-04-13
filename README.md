# challenge_1_ev3_robot_wander

EV3 Lego education robot kit

Project Description:

Design, construct, program, test, and demonstrate a mobile robot with the following behaviors:

Wandering:

This behavior emulates the non-deterministic way in which various animals explore an unknown environment. Animals do not move in a straight line until they sense something that they want to obtain. Rather they spend a great deal of time zig-zagging in a semi-random pattern called a biased random walk (or drunken sailor walk) as opposed to a pure random walk. This pattern has a generally forward motion with swings to the right or left that are at random intervals and for random amounts of time. Your robot, when not encountering an obstacle, should demonstrate a biased random walk as shown in the diagram at the end of this document. For full credit the biased random walk should consist of smooth curves, not connected line segments.

Object Detection and Reaction:

Bumpers are used to detect obstacles in front of the robot. The required reaction is relatively simple. If an object is detected on the right side (only the right bumper is depressed) then the robot should back up a short distance, turn to the left and resume wandering. Similarly, if an object is detected on the left, it should perform a mirror image response. If both bumpers are depressed (maybe within 10 milliseconds of one another?), the robot should make a sound, back up a short distance, pause for 2 seconds without moving, then turn in a random direction and resume wandering.
