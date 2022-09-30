# FLR--Flight-Computer
There are numerous flight computers available in the market. My goal was to design a flight computer with components that have reasonably low pricing to reduce the overall production cost, available in breakout boards, and widely available.

This Flight Computer for Landing Model Rocket is capable of:
1. Calculating Orientation
2. Calculating Altitude
3. Controlling pyros for deploying parachute and landing legs
4. Controlling two servo motors
5. Logging flight data
6. Accessing flight data

=> For orientation sensing on the rocket, IMU - Inertial Measurement Unit MPU-6050 is used with a built-in gyroscope and an accelerometer sensor.

=> For altitude sensing, BMP280 Barometric Pressure Sensor is used which measures the atmospheric density of the air surrounding it and it gets lower as you get higher up into the atmosphere. By measuring the change in atmospheric density we determine how high the rocket is above the ground.

=> N-channel mosfets are used to control parachutes, landing-like deployments, and firing motors.

=> Main brain of the computer is the widely available Atmega328 processor.

=> To log and access the flight data, SPI - Serial Peripheral Interface flash chip is used along with MicroSD Card.

