# SphereBot
Still being built - will be robot sphere!

### Electrical box  
- Motors Controller: L9110S, 2.5-12V 
- Arduino Nano: Version IOT33 

### Senors
- Latch Switch 
- Ultrasonic Sonic Sensor 

### Motors
- 6V micro geared 30 RPM DC “GA12-N20” 

### Wheels  
- Seal Half-Caps for handrailing 
- Slick metal sphere, with small surface area might have trouble with keeping traction… We can add some rubber tape for friction 

### Batteries
- 9V battery to run the Arduino 
- 6V battery to run the motor controllers 
 
### Wiring Diagrams
The motors are powered off of a 'high voltage supply' and NOT the regulated 5V. Don't connect the motor power supply to the Arduino's 5V power pin. This is a very very very bad idea unless you are sure you know what you're doing! You could damage your Arduino and/or USB port! 
