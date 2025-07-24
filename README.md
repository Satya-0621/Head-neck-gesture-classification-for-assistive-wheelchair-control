This project implements a gesture-controlled wheelchair operated using head tilt movements detected by the MPU6050 accelerometer + gyroscope sensor.
The MPU6050 captures tilt direction and sends analog signals to the Arduino UNO, which processes and digitizes them.
These digital signals are encoded using the HT12E encoder and wirelessly transmitted to the receiver side.
The HT12D decoder receives and decodes the signal, passing it to the L293D motor driver IC, which activates the motors via relays.
The system enables intuitive, hands-free wheelchair navigation and can be further enhanced with features like auto-stop and obstacle detection.

