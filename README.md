#Rajo Device 
Rajo device is used to collect information details on immunization for children and uses the guardians fingerprint to secure and verify the information.

#Getting Started
Welcome to the setup guide for Rajo device.This guide will help you setup the device and get it ready for use.

#Prerequisites
Before you start, make sure you have the following:

Raspberry Pi model 3
MicroSD card (32 GB)
Power supply for the Raspberry Pi
USB fingerprint sensor (compatible with Raspberry Pi)
Computer with an internet connection
HDMI monitor, keyboard, and mouse (for initial setup)
Access to your Wi-Fi network


Step 1: Prepare the Raspberry Pi
Insert the MicroSD card into your computer.
Download the latest version of the Raspberry Pi OS from the official website (https://www.raspberrypi.org/software/operating-systems/).
Use Raspberry Pi Imager to flash the OS onto the MicroSD card.


Step 2: Initial Setup
Insert the flashed MicroSD card into the Raspberry Pi.
Connect the Raspberry Pi to an HDMI monitor, keyboard, and mouse.
Power on the Raspberry Pi using the provided power supply.
Follow the on-screen instructions to set up the basic configurations, including language, timezone, and password.


Step 3: Connect to Wi-Fi
Once the Raspberry Pi is booted up, click on the Wi-Fi icon on the top-right corner of the screen.
Select your Wi-Fi network and enter the password to connect.


Step 4: Install Required Software
Open the terminal on the Raspberry Pi.
Update the package list and upgrade the installed packages:
sudo apt update
sudo apt upgrade
Install any necessary software libraries and dependencies for your fingerprint sensor.

Step 5: Connect the Fingerprint Sensor
Turn off the Raspberry Pi.
Connect the USB fingerprint sensor to an available USB port.
Power on the Raspberry Pi.

Step 6: Test the Fingerprint Sensor
Open the terminal and navigate to the directory where you've installed the fingerprint sensor software.
Run a test script or application provided by the sensor manufacturer to verify that the sensor is functioning correctly.

Step 7: Start Using the Device
Your Raspberry Pi-based IoT device with a fingerprint sensor is now set up and ready to use. 

