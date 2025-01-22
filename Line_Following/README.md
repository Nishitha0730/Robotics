# Line Following with e-puck in Webots

This project demonstrates two different approaches to implementing a line-following robot using the e-puck robot in the Webots simulation environment. The project includes two scenarios: one using basic line-following with two IR sensors, and another using a PID controller with five IR sensors for more precise line tracking.

## Videos

- **Basic Line Following**
  [Watch the video](https://1drv.ms/v/c/66efd464b4ddcd14/ETggr_IWoBhPhYKYsZFTYy8BdxaQGmwt41H7Y_exIZLM7w?e=OT5Rwh)

- **PID Line Following**
  [Watch the video](https://1drv.ms/v/c/66efd464b4ddcd14/EXyD_SSI-PRKkcOt2qDjb5YBVhGo1O-8kZoXEb0OSu_ogA?e=ZQuS0D)

## Features

### Scenario 1: Basic Line Following
- Utilizes two IR sensors to detect the black line.
- Implements simple conditional logic to adjust the robot's direction based on sensor inputs.
- Ideal for understanding the fundamentals of line-following robots.

### Scenario 2: PID Line Following
- Employs five IR sensors for enhanced line detection and tracking.
- Uses a PID (Proportional-Integral-Derivative) controller to ensure smooth and accurate movement along the line.
- Demonstrates advanced line-following techniques suitable for more challenging environments.

## Prerequisites
- Webots installed on your computer.
- Basic understanding of programming in Python.

## How to Use
1. Clone this repository to your local machine.
2. Open the Webots simulation environment.
3. Load the respective world files for each scenario.
4. Run the simulation to observe the e-puck robot's behavior.

## About the e-puck Robot
The e-puck robot is a small mobile robot designed for education and research in robotics. It is equipped with:
- Multiple IR sensors for proximity and line detection.
- Compact design suitable for simulated and real-world tasks.

## Future Work
- Extend the PID controller for dashed line following.
- Implement dynamic obstacle avoidance while line-following.

## Feedback
Feel free to contribute to this repository or share your feedback. For any questions, open an issue or contact me.

---

Thank you for checking out this project! 🌟
