# ENGR 323L PID Motor Control Project

The SiliconLab 8051F120 evaluation board will be used to perform DC motor speed control. To achieve the desired goal for this project, the specifications that the DC motor embedded system must satisfy are:

Sending Pulse-Width Modulation (PWM) signal to drive the DC motor at various speed by manipulating the duty cycle. PWM signal will be generated by the programmable counter array (PCA) of the C8051F120 board.
-Being able to adjust the desired speed of the DC motor using the potentiometer.
-Establishing a feedback system to measure the actual speed of the DC motor.
-Implementing a PID controller to make timely adjustment of the duty cycle to maintain the desired speed for various loads on the shaft of the motor.
-Displaying the desired speed and actual speed of the DC motor on the 16×2 LCD Display.

by Adam Woo, Takuto Wada

## Hardware and Software

Here is a list of the selected hardware:

| Component | Part |
| --- | --- |
| H-Bridge | SN754410 |
| Operational Amplifier | SN741 |
| Microprocessor | SiliconLab 8051F120 |
| DC Motor | generic brushed motor |
| IDE | Silicon Laboratories |
