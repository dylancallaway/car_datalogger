# Repository for OBD2 + Other Car Datalogger

##### Hardware
- Raspberry Pi Model 3B+
- MPU6050 breakout board.
- OBD2 to USB cable.

##### Setup
-OBD2 on car to USB on RPi.
-USB on car to micro-USB on RPi.

##### Organization
- Modules
  - Class for CAN data via OBD2 port and USB (Python-OBD).
    - Speed.
    - RPM.
    - Coolant temperature.
    - TPS.
    - AFR.
    - MAF.
  - Class for IMU (MPU6050) via I2C module (Python-SMBus).
    - Accelerometer.
    - Gyroscope.