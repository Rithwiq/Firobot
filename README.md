# Firobot
Code repository for Arduino based RF swarm communication network

This project is to explain the swarm based radio frequency communication system codes used for the Firobot Project.

Communication Hardware:
1. nRF240LI Module
2. Elegoo Uno R3 (Cheaper Arduino Alternative)

The Firobots used will have the communication hardware system connected to the sensor array consisting of the MLX90614 (I.R temperature sensor) and BME 680 (gas sensor). The fire extinguishing mechanism is also connected to the same hardware. When a Firobot is in use, the ACS (Agent Communication System) sends out data from the sensors at real time to the ground control or MCS (Master Communication System). The MCS also has the same communication hardware which is connected to a computational unit such as a laptop or PC. Each of the ACS will send data based on their sensor values to the MCS. 

Communication Code:
Based on the RF24 Library
