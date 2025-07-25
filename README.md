# MathWorks-Group-3-Project
In this project, we created an optimized drone frame using the principles of statics and physics. Our drone is a carbon fiber quadcopter (4 motors) with four arms and a central body for storing a battery and circuitry.

We began by coming up with some rough design ideas. CAD software was used to create 3D models for better visualization (created by Ava). Of the designs created, we collectively decided to proceed with this one:

<img width="470" height="350" alt="InitialDrone3" src="https://github.com/user-attachments/assets/4bf19aa3-45e4-41e9-b287-9eadbf4f0c67" />

We then started working out the details of the design, the first being the motors. The motors are the only outside weight that the drone will be carrying, so knowing their exact details is crucial to optimizing the drone itself. Each motor provides 1 kg of thrust, and we approximated its dimensions (by averaging the most common drone motors on the market) as follows (created by Ava):

<img width="211" height="223" alt="Drone3MotorDim" src="https://github.com/user-attachments/assets/e4deb042-49b2-4a83-b6a7-7fc3a60095c9" />

With the motors sorted out, we could determine the optimal measurements for the drone frame. This includes the exact measurments, the material, and preliminary calculations for details like density, weight, thickness, and the exact details of the shape (created by Gavin):

<img width="540" height="322" alt="Drone3Calculations" src="https://github.com/user-attachments/assets/63bafd7e-b8c7-431d-b274-340c9801b029" />

These measurements were used to create an engineering drawing of the drone for better visualization in Onshape (created by Ava):

<img width="862" height="664" alt="Drone3DrawingFINAL" src="https://github.com/user-attachments/assets/c7aba7ae-dcd1-4063-9b19-ec42e160408c" />

From there, The code was developed in stages: first by modeling the physical geometry and mass, then applying statics principles to analyze forces and moments, and finally by validating results through plotted visualizations. Parameters like body thickness, payload mass, and motor position were modularized to allow rapid testing and design adjustments. The MATLAB code models a quadcopter using real-world material and geometry inputs, then calculates mass, thrust, bending moments, and center of mass. The figures such as the drone layout, shear force diagram, and moment diagram were generated through simulations to visually verify load distribution and structural balance (created by Alexis). 

<img width="1023" height="685" alt="Screenshot 2025-07-25 112449" src="https://github.com/user-attachments/assets/7816a4a1-8e98-4c20-b9a6-5d26e1865087" />

<img width="1028" height="677" alt="Screenshot 2025-07-25 112249" src="https://github.com/user-attachments/assets/bac707a3-4d85-47b1-b183-6cb4666d1c54" />

Here is the final model of our drone (created by Ava):

<img width="584" height="323" alt="Drone3CAD" src="https://github.com/user-attachments/assets/a8f1e3e8-32f9-41bc-89af-4d58dd72bcb3" />

Here is the link to view the final drone model in Onshape:
https://cad.onshape.com/documents/20d0fcabb8acea3ea6179fe3/w/0e8293d668412b3fffb13cd4/e/7eac579bb005529b925857f8?renderMode=0&uiState=6883c4cd602d2243efea5c5c

(GitHub Repository put together by Ava & Alexis)
