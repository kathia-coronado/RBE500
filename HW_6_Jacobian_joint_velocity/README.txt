Problem set VI-1

Use the Robotic Systems Toolbox in Matlab to calculate the forward kinematics of the Denso's HSR robot.
You can use the example of the Puma560 robot available in the toolbox:
"Build Manipulator Robot Using Denavit-Hartenberg Parameters" 
https://www.mathworks.com/help/releases/R2018a/robotics/ref/robotics.rigidbodytree-class.html (Links to an external site.)
Using the function "getTransform" save and print the end-effector trajectory with the following joint input: 
First joint: −pi/4·sin(2pi∗t)
Second joint: pi/2·sin(4pi∗t)
Other joints: zero
Problem set VI-2.

Denso's HSR robot again (Week 1,2,3), Open the product specification LINK.     (Links to an external site.)Download a catalog (Links to an external site.). Consider 480 mm reach model with 100 mm z-stroke , Write DH parameters table. Use the DH parameters you created in Week 2. Consider, again, link ends at Link4.
VI-2-1
Derive Jacobian for this robot with numeric values, and write it clearly in the submission. Use the lecture video effectively. 
Compare the derived Jcobian with one created using the "geometricJacobian" function
VI-2-2
Create trapezoidal velocity profiles for each joint using trapveltraj function of the Robotics Toolkit.
Using the J you created above (either your own or from geometricJacobian, compute linear and angular velocity of the all joints and tip of the Link 4. 