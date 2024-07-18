# An IoT Based Interactive Robot

### INTRODUCTION
<p align="justify">The goal of this project is to create an interactive robot that can recognize individuals through facial recognition and assess their temperature during a handshake. If the person's temperature is normal and they are recognized, the robot greets them by name with a voice greeting. Otherwise, it welcomes them as a guest.<br>
Beyond its interaction system, its practical application extends to the college laboratories, where it can significantly streamline attendance management. This not only enhances operational efficiency but also promotes a safer and more hygienic environment within educational institutions.</p>

### APPROACH
<p align="justify">To address this problem, a system was designed that integrates machine learning for facial recognition with hardware components for temperature detection and movement. The solution involves using OpenCV and SVMs for accurate facial recognition, servo motors for the handshake mechanism, and temperature sensors to assess the person's health status.</p>

### OVERVIEW OF THE PROJECT
<p align="justify">
With a particular focus, this project tries to shed light on the following modules.<ol>
<li>Image Acquisition</li>
<li>Image Processing</li>
<li>Facial Recognition</li>
<li>SVM Comparison</li>
<li>Temperature Measurement; and</li>
<li>Voice Greeting</li>
</ol></p>

## SYSTEM REQUIREMENTS
### HARDWARE REQUIREMENTS
<p align="justify">
Listed below are the primary hardware components utilized in building the prototype, along with their significance.<ul>
<li>Raspberry Pi Camera Module v1: For capturing images of the person for facial recognition.</li>
<li>Raspberry Pi 4B Microcontroller Board: The central processing unit for the robot, running the facial recognition algorithms and controlling other hardware components.</li>
<li>Servo Motor MG995: Used to simulate the handshake movement.</li>
<li>L298N Motor Driver: Controls the servo motor's movement.</li>
<li>MLX90614 Temperature Sensor: Measures the temperature of the person during the handshake.</li>
<li>Speaker for Voice Output: Provides audio feedback by greeting the person.</li>
<li>32 GB SD Card: Provides additional storage for the Raspberry Pi.</li>
<li>HDMI Cable: Connects the Raspberry Pi to a monitor for setup and debugging.</li>
<li>USB Cables: Connect and power various components.</li>
</ul> </p>

### SOFTWARE REQUIREMENTS
<p align="justify">
The software requirements for this project are listed below.<ul>
<li>OpenCV: Used for image processing and facial recognition.</li>
<li>dlib: Facilitates machine learning tasks such as face detection and feature extraction.</li>
<li>face_recognition: Simplifies the process of facial recognition by providing easy-to-use functions.</li>
<li>gpiozero: Controls the GPIO pins on the Raspberry Pi.</li>
<li>MLX90614 Module: Interfaces with the MLX90614 temperature sensor.</li>
<li>RPi.GPIO: Another library for controlling the Raspberry Pi GPIO pins.</li>
<li>pyttsx3: Text-to-speech conversion library used for generating voice greetings.</li>
</ul>
</p>
