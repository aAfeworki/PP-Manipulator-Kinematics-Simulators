# PP-Manipulator-Kinematics-Simulators
Interactive Python-based simulators for the PP (Prismatic–Prismatic) manipulator, featuring forward kinematics with slider control, forward kinematics driven by inverse kinematics solutions, and an inverse kinematics simulator.



This repository provides interactive simulators for the PP (Prismatic–Prismatic) Manipulator, implemented in Python using `matplotlib`.  
It covers both forward and inverse kinematics, enabling visualization and understanding of planar manipulators with two prismatic joints.  



🚀 Features
- Forward Kinematics (Slider-Controlled)
  Visualize the manipulator by adjusting prismatic joint displacements interactively with sliders.
  
![image alt](https://github.com/aAfeworki/PP-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_PP_manipulator_with_Slider.png?raw=true)

- Forward Kinematics (IK-Driven)
  Drive the manipulator using joint displacements calculated from the inverse kinematics solver.

![image alt](https://github.com/aAfeworki/PP-Manipulator-Kinematics-Simulators/blob/main/FK_Simulator_for_PP_Industrial_Robot.png?raw=true)  

- Inverse Kinematics Simulator
Enter the equation of a curve on the User Interface to generate joint angles that position the manipulator’s end-effector.
  
![image alt](https://github.com/aAfeworki/PP-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_PP_manipulator_with_Simulator.png?raw=true)

![image alt](https://github.com/aAfeworki/PP-Manipulator-Kinematics-Simulators/blob/main/IK_Generator_for_PP_manipulator_with_Simulator%20User%20Interface.png?raw=true)


📂 Project Structure

PP-Manipulator-Kinematics-Simulators
      FK_Simulator_for_PP_manipulator_with_Slider.py
      FK_Simulator_for_PP_Industrial_Robot.py
      IK_Generator_for_PP_manipulator_with_Simulator.py
      README.md



🛠 Requirements
- Python 3.8+
- `numpy`
- `matplotlib`
- `tkinter`




▶️ Usage
Run any simulator with:

      FK_Simulator_for_PP_manipulator_with_Slider.py

      FK_Simulator_for_PP_Industrial_Robot.py

      IK_Generator_for_PP_manipulator_with_Simulator.py


🎯 Applications

      Educational tool for understanding the kinematics of PP manipulators.


      Useful for robotics students, instructors, and researchers.


      A base framework for extending into dynamics, control, and trajectory planning.



📜 License
This project is licensed under the MIT License.

👨‍💻 Developed by Afework Alemu
