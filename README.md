# DroneKit_Velocity_Based_Movement

This python script implements DroneKit Python API to send velocity commands such as forward and yaw to a quadcopter drone running ArduPilot.

It was originally written to run on a Navio2/RPi quadcopter drone running ArduPilot. The script is run from the Raspberry Pi (RPi) and connects to the "vehicle" using a written function in the script. Then there are functions to set the velocity and yaw of the vehicle. These functions are then implemented in the "mission" with loops using time.sleep to send transient velocity commands to the drone which can be altered and programmed to run autonomously.
