# Robot Dog Mechanical Design

## Introduction

This project presents a preliminary mechanical design of a simple robotic dog. The main objective is to understand the basic mechanical principles of quadruped robots.

## Objectives

- Design the robot body.
- Design the legs.
- Determine the number of joints and Degrees of Freedom (DOF).
- Select suitable motors.
- Calculate the torque for one joint.
- Study stability and center of gravity.
- Suggest a manufacturing method.
- Discuss expected mechanical challenges.

## Body Design

The robot has a rectangular body designed to provide a stable platform for all mechanical and electronic components. The battery and controller are placed near the center of the body to improve weight distribution and maintain balance.

The robot has four legs, with each leg connected to the body through mechanical joints driven by servo motors. This simple body structure provides stability while keeping the design lightweight and easy to manufacture.



## Leg Design

The robot has four identical legs to ensure balanced movement. Each leg consists of two joints:

- Hip Joint: Connects the leg to the robot body and allows forward and backward movement.
- Knee Joint: Allows the leg to bend while walking.

This simple two-joint design reduces mechanical complexity while providing enough flexibility for basic walking and standing.




## Degrees of Freedom (DOF)

Degrees of Freedom (DOF) describe the number of independent movements that a robot can perform.

Each leg has:
- 1 Hip Joint (1 DOF)
- 1 Knee Joint (1 DOF)

Since the robot has four legs:

2 DOF × 4 Legs = 8 DOF

The robot has a total of 8 Degrees of Freedom, which provides enough flexibility for basic walking and standing movements.





## Motor Selection

The selected motor for this project is the MG996R Servo Motor. It is a popular choice for educational robotics because it provides high torque, is easy to control, and is affordable. Each joint is powered by one servo motor to achieve smooth and reliable movement.

---

## Torque Calculation

To estimate the required torque for one joint, the following equation is used:

Torque = Force × Distance

Example:

- Mass = 0.5 kg
- Gravity = 9.81 m/s²
- Distance = 0.1 m

Force = 0.5 × 9.81 = 4.9 N

Torque = 4.9 × 0.1 = 0.49 N·m

Therefore, the selected motor should provide more than 0.49 N·m of torque to move the leg safely.

---

## Stability and Center of Gravity

The robot's stability depends on proper weight distribution. The battery and controller are placed near the center of the body to keep the center of gravity low and balanced. This helps the robot stand and walk without tipping over.

---

## Manufacturing Method

The proposed manufacturing method includes:

- 3D printing for the robot body.
- Aluminum or plastic brackets for the leg structure.
- Servo motor brackets for mounting the motors.
- Screws and nuts for assembly.

This method is simple, cost-effective, and suitable for educational projects.

---

## Mechanical Challenges

Some expected mechanical challenges include:

- Insufficient motor torque.
- Poor balance during walking.
- High battery consumption.
- Joint wear after long-term use.
- Increased robot weight due to additional components.

These challenges can be reduced by selecting suitable materials, improving weight distribution, and using appropriate motors.

---

## Conclusion

This project presents a preliminary mechanical design of a simple quadruped robot. The design includes the body structure, leg mechanism, motor selection, torque estimation, stability analysis, manufacturing method, and expected mechanical challenges. It provides a strong foundation for understanding the basic principles of robotic mechanical design.

---

## References

1. Siciliano, B., & Khatib, O. *Springer Handbook of Robotics*. Springer.
2. MG996R Servo Motor Datasheet.
3. Peter Corke. *Robotics, Vision and Control*. Springer.