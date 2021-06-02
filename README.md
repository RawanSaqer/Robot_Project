# Robot_Project
/
/
/
Project
Consider that a UAV blocking an exit consists of a helicopter body with a camera that can pan and tilt independent of the body (i.e., the body can stay in one place while the camera moves). The UAV is programmed to have three behaviors: watching, approaching, and threatening. In watching, the UAV is stationary at above eye level, but the camera scans the area in front. In approaching, the UAV moves to eye level, and the camera tracks the center of the crowd. In threatening, the UAV performs random motions if the crowd gets too close. The UAV has the following motor schemas (with arguments missing for brevity): fly-at-given-altitude(), body-turn(), body-move-sideways(), body-move-random-3D(), and camera-pan-tilt() . It has the following perceptual schemas: detect-motion() and detect-object-distance().
Design the behavioral scheme using:
/
a. potential fields methodology.
b. subsumption architecture methodology.
