
# Discrete PID Control for Waypoint Tracking of an IMU-Based Tendon Driven Continuum Robot

This project started as a lab project, grew into final thesis project, and was published at the ICSMECH 2026 conference. For more details: https://ieeexplore.ieee.org/document/11647198

**Tools Used**
- **MATLAB:** data acquisition, visualization, and controller implementation
- **Arduino IDE:** motor and microcontroller programming, with a Kalman filter and discrete PID control
- **Autodesk Inventor:** mechanical design and technical drawings
- **KiCad**: PCB design


## Results

During testing, the maximum roll and pitch error reached approximately 38°. This error was most pronounced during vertical motion, when the silicone cord backbone could not maintain structural stability. Its flexibility let the platform deflect under changing load and acceleration, so the controller could not fully correct the orientation. The result points to the backbone's mechanical stiffness, rather than the control algorithm, as the main limit on performance.









## Demo

Insert gif or link to demo

## Documentation
**Trajectory Tracking Method:**
![System Design Image](https://github.com/naufalra/Discrete-PID-Control-for-Waypoint-Tracking-of-an-IMU-Based-Tendon-Driven-Continuum-Robot/blob/main/Trajectory%20Tracking%20Method.jpg?raw=true)

**System Design** 
![System Design Image](https://github.com/naufalra/Discrete-PID-Control-for-Waypoint-Tracking-of-an-IMU-Based-Tendon-Driven-Continuum-Robot/blob/main/System%20and%20GUI%20design.jpg?raw=true)

**Mechanical Design**
![System Design Image](https://github.com/naufalra/Discrete-PID-Control-for-Waypoint-Tracking-of-an-IMU-Based-Tendon-Driven-Continuum-Robot/blob/main/Mechanical%20Design.jpg?raw=true)

**Electronics Design**
![System Design Image](https://github.com/naufalra/Discrete-PID-Control-for-Waypoint-Tracking-of-an-IMU-Based-Tendon-Driven-Continuum-Robot/blob/main/Electronics%20Design.jpg?raw=true)

**PID Trajectory Result**
![System Design Image](https://github.com/naufalra/Discrete-PID-Control-for-Waypoint-Tracking-of-an-IMU-Based-Tendon-Driven-Continuum-Robot/blob/main/Trajectory%20Tracking%20Result.jpg?raw=true)
## Acknowledgements

I would like to express my sincere gratitude to **Syahrul Abidin**, my project partner, for his collaboration and contributions throughout this work, and to **Jans Hendry**, our supervisor, for his guidance and support.

