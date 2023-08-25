```
Descriptive details of Assignment:
```
 Mission 1: Reactive vision-based navigation
o The goal of the robot will be to move forwards while taking always right
turns. The behaviour must be as safe and smooth as possible, trying not to
leave the tarmac at any point in time. The robot does not need to follow a
particular lane at any point (in any mission).
 Mission 2: Object detection
o The goal of the robot will be to build on top of your previous mission and
detect stop signs. When one is in front of the car (and only then) the robot
must stop before it and continue moving after one second. In this mission,
you will not be assessed based on how good the navigation is, although it
has to work for the car to be able to move. The task must be done through
vision, not Webot’s simulated object detection API. You can use use an adhoc method or any stop sign detector. Third-party modules are allowed as
long as their use is acknowledged. If using machine learning, training with
your own data will be taking into consideration.
 Mission 3: Keeping the battery charged while navigating
o The goal of the robot will be to take left and right turns at random with equal
chances for each intersection until it runs low on battery. When that
happens, the robot must ensure to go to the charging area (the intersections
should no longer be taken randomly) to avoid running out of battery. After it
is completely charged (90% charged), the robot must return to its initial goal.
o Note: the car will have a GPS sensor for this mission (see rasrobot.py).
 Mission 4: Integration mission
The goal of this mission will be to integrate previous missions i.e., to make
the robot move as in Mission 3, while stopping at stop signs and recharging.
o Note: In this mission the car will also have a GPS sensor. You can use it to
improve the features developed for any of the previous missions