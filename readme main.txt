Helmet Main Readme
------------------

Welcome to the Autonomous Visor Cycling Helmet GUI by Ning Xuan Tan, Andrew Shacker, and Xander White, 2018.

Guide
1. Connect the myRio to WiFi/USB.
2. Follow the "Integrating Android Devices with NI Sofware" tutorial at: http://www.ni.com/example/31558/en/ to use your phone's camera for vehicle detection and tracking.
*For a quickstart, choose an existing webcam from the Vision Acquisition wizard.
3. Run the myRio VI labeled "Main_myRIO_helmet.vi" from the Autonomous Visor Helmet project tree (under the myRio folder).
4. Run the "PC_Main_Helmet.vi" under the PC folder. To enable full-screen, exit the VI, update the resolution constants in the block diagram, and remove the diagram disable structure.
5. Set your desired settings in each tab on the GUI.
6. Your helmet is ready to use!

Modes
Manual: Deploys visor only when button0 on myRIO is pressed.
Auto: Deploys visor when fall is detected.
Safe: Deploys visor when fall is detected or vehicle detected and approaching at or within minimum set rate (and range). 

Primary Indicators
Rear Vehicle: Left and Right boolean indicators show which direction the car being tracked by your camera is shifting behind you using motion estimation.
Visor: Retract will retract the visor if it has been deployed. Visor Deployed shows whether a signal has been sent to the servo to deploy the visor.

Credits
We would like to thank the following individuals for their help with our project:
Prof. George Anwar     
GSI Drew Sabelhaus     
Bola Malek (Triathlete)