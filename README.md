# Raspbery-Pi-4-with-DC-Geared-Motor

Motor Used = DC Geared Motor 150 RPM (link to the motor http://www.nex-robotics.com/products/motors-and-accessories/150rpm-side-shaft-dc-gear-motor-with-position-encoder.html)
#### ![image](https://user-images.githubusercontent.com/59818448/151837966-1b5f4f54-2024-4595-afac-dff493952412.png)


# DC Motor Introduction:

150RPM gear motor with position encoder is a high performance DC gear motor with optical position encoder. It gives 540 pulses per revolution of the output shaft. Motor can run smoothly from 4V to 12V. Position encoders are used in applications that requires precise angle of rotation of the motor such as robotics, automation etc.

## Specifications:

Supply:    12V (Motor runs smoothly from 4V to12V)

Position encoder resolution: 540 pulses per revolution of the output shaft
No Load RPM: 150RPM @ 12V

Stall Torque: 15kg-cm @ 12V

Encode Typt : Optical

Diameter: 37mm

Length (With Shaft and Back Connector): 92.70mm

Shaft diameter: 6mm

Gear ratio: 1:60
Position encoder supply: 4.5V or 5.5V
Position encoder current requirement: 10mA to 20mA
6 pin Relimate connector for interfacing

## Interfacing:

Sturdy  relimate connector is used for position encoder signals and motor power. Position encoder can be powered within 4.5V to 5.5V DC.

![Screenshot (122)](https://user-images.githubusercontent.com/59818448/151838605-9877add0-5617-4b87-9d9e-62bae545eaa0.png)



# Motor Driver

## # ![image](https://user-images.githubusercontent.com/59818448/151838856-9c4d1e80-487b-4ce8-b402-3f199c5e2c4b.png)


L298 Dual H Bridge Motor Driver

# Pin Connections

## Motor Driver to Raspbery pi 4 B
IN1 = GPIO 23
IN2 = GPIO 24
ENA = GPIO 25
GND = GND

## Motor Driver WIth power Source

GnD to GND
Power to 12v

## Motor Driver tO Motor

RIght Motor
Out 1 = M1
out 2 = m2

Left Motor
Out3 = M1
Out 4 = m2
