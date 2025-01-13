# scan-and-track-sonar
This is set up for a ultra-sonic sensor (HCSR04 ultrasonic sensor), in which the sonar scans the area and when a something is detected the sonar will complete is cycle and  specifically scan or track the area where the object was until nothing is detected.
you will need: 
Arduino Uno R3,
HCSR04 ultrasonic sensor,
a servo motor,
a breadboad ,
some male to male and female to male jumper wires

the power lines and GRD of both the sensor and servo motor should be connected to 5v and GRD in the arduino respectively. I used a breadborad to make easier, connect the sensor to the servo motor. connect the cables them as the image shows:
![ACQ](https://github.com/user-attachments/assets/56b47e4f-8b62-418b-ba02-1212491730e4)
download prossing IDE app to get the radar like interface. The code for it will be in 'acq_proc' folder.
![image](https://github.com/user-attachments/assets/a9798883-0f9f-40c3-9614-53f2f90a0b09)

note: the range of the sonar is reduce to 40 cm but it can work up to 400 cm.
