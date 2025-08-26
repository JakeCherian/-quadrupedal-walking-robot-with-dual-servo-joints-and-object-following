<a name="readme-top"></a>
<div align="center">
  <a href="https://github.com/JakeCherian/QuadTrackBot">
  </a>

<h3 align="center">Object-Following Quadrupedal Walking Robot with Dual-Servo Joint Structure</h3><br>
</div>

## Introduction

QuadTrackBot is an innovative quadrupedal robot designed to mimic biological locomotion through dual-servo leg joints. Unlike traditional single-servo or wheeled robots, this system demonstrates multi-directional walking, including forward, sideways, and pivoting motions. Equipped with ultrasonic sensing and Arduino-based control, the robot can detect and follow objects while maintaining stability and adaptability in indoor environments.

## Key Features

- **Dual-Servo Joint Design**: Each leg uses two servo motors for horizontal sweep and vertical lift, enabling smooth and flexible gaits.
- **Multi-Directional Movement**: Capable of forward walking, sideways shuffling, and pivoting without turning its body.
- **Object-Following Capability**: Integrated HC-SR04 ultrasonic sensor for obstacle detection and target tracking.
- **Arduino + PCA9685 Control**: Precise servo synchronization and sensor feedback integration.
- **3D-Printed Body**: Lightweight and durable structure with optimized weight distribution and easy assembly.

## Technology Stack

This project combines robotics, embedded systems, and sensor-driven navigation:

1. **Robotics**: Four-legged platform with dual-servo joint structure for enhanced locomotion.
2. **Embedded Systems**: Arduino Uno with PCA9685 servo driver for multi-servo synchronization.
3. **Sensors**: HC-SR04 ultrasonic sensor for real-time object detection and following.
4. **3D Printing**: Custom-designed body parts for housing electronics and supporting servo motors.

## Applications

QuadTrackBot can serve as a practical demonstration and research platform for:

- Robotics and automation experiments  
- Object-tracking and following systems  
- Educational demonstrations in locomotion and control  
- Indoor navigation research  

<!-- ABOUT THE PROJECT -->
## System Operation and Control Flow

The quadrupedal robot operates through the coordinated action of servo-driven joints and sensor feedback.

### Leg Movement and Gaits

- **Horizontal Control**: One servo manages sideways sweeping of each leg.  
- **Vertical Control**: Another servo lifts and lowers the leg for step execution.  
- **Gait Patterns**: Includes forward walking, sideways shuffle, and center-pivot rotation for agile navigation.  

### Object Detection and Following

- The **HC-SR04 ultrasonic sensor** detects objects and obstacles in real time.  
- Sensor readings are processed by the Arduino, which adjusts gait patterns accordingly.  
- Enables smooth object following even when the target moves unpredictably.  

### Servo Synchronization

- The **PCA9685 servo driver** ensures stable and simultaneous control of all 8 servo motors.  
- Smooth trajectory generation prevents jerks and ensures natural movement.  
- Power system with dual Li-ion batteries provides stability and runtime.  

### System Stability and Safety

- Built-in code safeguards prevent servo overextension.  
- Optimized gait patterns distribute load evenly across legs.  
- Modular design allows quick maintenance and adjustments.  

---

## Visual Reference of the Robot
### Image 1
<div class="image-container">
  <img src="Quadruped_1.jpg" alt="Quadruped Robot Front View" width="300" height="300">
</div>

### Image 2
<div class="image-container">
  <img src="Quadruped_2.jpg" alt="Quadruped Robot Side View" width="300" height="300">
</div>

### Circuit Diagram
<div class="image-container">
  <img src="Quadruped_Circuit.jpg" alt="Circuit Diagram" width="600" height="350">
</div>
<br>

---

## Conclusion and Future Development

### Project Achievement
The QuadTrackBot successfully demonstrates the feasibility of using dual-servo joints for quadrupedal locomotion. With integrated ultrasonic sensing, the system achieves basic object-following and multi-directional movement.

### Key Accomplishments
- Completed mechanical assembly with 3D-printed structure and mounted servos.  
- Developed base code for servo movement and ultrasonic sensing.  
- Achieved multi-gait movement patterns for forward, sideways, and pivot navigation.  

### Limitations and Challenges
- Current implementation supports only basic object-following behavior.  
- Gait synchronization still requires optimization for smoother transitions.  
- Limited by ultrasonic sensing range and accuracy.  

### Future Enhancements
1. **Advanced Object Tracking**  
   - Integrate computer vision for enhanced target recognition.  
   - Improve sensor fusion for more reliable obstacle avoidance.  

2. **Movement Optimization**  
   - Implement dynamic gait switching for real-time adaptability.  
   - Add closed-loop feedback for precision control.  

3. **System Improvements**  
   - Extend battery life with optimized power management.  
   - Develop modular software framework for additional sensors.  

### Applications and Impact
This project has significant potential in:  
- Indoor exploration and navigation  
- Object-following robots for assistance and service  
- Research platforms in gait control and biomimicry  
- Educational robotics for demonstrating advanced locomotion  

---

## Team Members

* Jacob Cherian - jakecherian10@gmail.com  
* A Abishek - (email)  
* Abhinav Balakrishnan - (email)  

Project Link: [https://github.com/JakeCherian/QuadTrackBot](https://github.com/JakeCherian/QuadTrackBot)  
