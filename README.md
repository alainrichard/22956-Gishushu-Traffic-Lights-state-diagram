# 22956-Gishushu-Traffic-Lights-state-diagram
state diagram Gishushu Traffic Lights State Machine
--------------------------------------------------

Specification (Narration)
------------------------

The Gishushu Traffic Lights system is designed to control vehicle and pedestrian traffic at intersections, ensuring safety and efficiency. The system operates in a cyclical manner through three primary states: Green, Yellow, and Red.

Green Light: Cars can go.

Yellow Light: Cars should prepare to stop.

Red Light: Cars must stop.

 States and Their Function
 -------------------------

Green Light State
-----------------

Duration: 30 to 60 seconds.

Action: Vehicles are allowed to proceed through the intersection while pedestrian signals remain red, indicating that pedestrians should not cross.

Transition: When the timer expires, the system transitions to the Yellow state.


Yellow Light State:
------------------

Duration: 3 to 5 seconds.

Action: This state signals drivers to prepare to stop. Vehicles that are too close to the intersection may continue through the light.

Transition: The system transitions to the Red state when the timer for the Yellow light expires.


Red Light State:
----------------

Duration: 30 to 60 seconds.

Action: Vehicles must stop at the red light. Pedestrian signals may turn green, allowing pedestrians to cross safely.

Transition: The system transitions back to the Green state when the red light duration expires.
