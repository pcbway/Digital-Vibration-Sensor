![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005.jpg "SENZ005") 

### Introduction

> What's the simplest way to check vibration with Arduino? Just vibrate this sensor,it is designed by PCBWay team and FizzyStudio team. Arduino can receive a digital signal. It's easy to acount and program in Arduino.
> Despite it's simple, you can make full use of it with creative thinking, like step counting, Crash warning light and so on.

### Specification

* Wide voltage range from 3.3V to 5V
* Standard assembling structure (two 3mm diameter holes with multiple of 5mm as distance from center)
* Easily recognitive interfaces of sensors ("A" for analog and "D" for digital)
* Icons to simplely illustrate sensor function
* High quality connector
* Immersion gold surface
* IO Type: Digital
* Switch life: up to 10 million seconds
* Open circuit resistance: 10Mohm
* Supply Voltage: 3.3V to 5V
* Interface: Digital
* Size:22x30mm

### Tutorial

#### Connection Diagram

![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005_2.png "Connection") 

#### Sample Code

    #define SensorLED   13
    //Connect the sensor to digital Pin 3 which is Interrupts 1.
    #define SensorINPUT  3  

    unsigned char state = 0;

    void setup() {
      pinMode(SensorLED, OUTPUT);
      pinMode(SensorINPUT, INPUT);
      //Trigger the blink function when the falling edge is detected
      attachInterrupt(1, blink, FALLING);  
    }

    void loop() {
      if (state != 0) {
        state = 0;
        digitalWrite(SensorLED, HIGH);
        delay(500);
      } 
      else
        digitalWrite(SensorLED, LOW);
    }

    //Interrupts function  
    void blink() {
        state++;
    }

#### Result
![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005.jpg "SENZ005") 

### Introduction

> What's the simplest way to check vibration with Arduino? Just vibrate this sensor,it is designed by PCBWay team and FizzyStudio team. Arduino can receive a digital signal. It's easy to acount and program in Arduino.
> Despite it's simple, you can make full use of it with creative thinking, like step counting, Crash warning light and so on.

### Specification

* Wide voltage range from 3.3V to 5V
* Standard assembling structure (two 3mm diameter holes with multiple of 5mm as distance from center)
* Easily recognitive interfaces of sensors ("A" for analog and "D" for digital)
* Icons to simplely illustrate sensor function
* High quality connector
* Immersion gold surface
* IO Type: Digital
* Switch life: up to 10 million seconds
* Open circuit resistance: 10Mohm
* Supply Voltage: 3.3V to 5V
* Interface: Digital
* Size:22x30mm

### Tutorial

#### Connection Diagram

![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005_2.png "Connection") 

#### Sample Code

    #define SensorLED   13
    //Connect the sensor to digital Pin 3 which is Interrupts 1.
    #define SensorINPUT  3  

    unsigned char state = 0;

    void setup() {
      pinMode(SensorLED, OUTPUT);
      pinMode(SensorINPUT, INPUT);
      //Trigger the blink function when the falling edge is detected
      attachInterrupt(1, blink, FALLING);  
    }

    void loop() {
      if (state != 0) {
        state = 0;
        digitalWrite(SensorLED, HIGH);
        delay(500);
      } 
      else
        digitalWrite(SensorLED, LOW);
    }

    //Interrupts function  
    void blink() {
        state++;
    }

#### Result
![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005.jpg "SENZ005") 

### Introduction

> What's the simplest way to check vibration with Arduino? Just vibrate this sensor,it is designed by PCBWay team and FizzyStudio team. Arduino can receive a digital signal. It's easy to acount and program in Arduino.
> Despite it's simple, you can make full use of it with creative thinking, like step counting, Crash warning light and so on.

### Specification

* Wide voltage range from 3.3V to 5V
* Standard assembling structure (two 3mm diameter holes with multiple of 5mm as distance from center)
* Easily recognitive interfaces of sensors ("A" for analog and "D" for digital)
* Icons to simplely illustrate sensor function
* High quality connector
* Immersion gold surface
* IO Type: Digital
* Switch life: up to 10 million seconds
* Open circuit resistance: 10Mohm
* Supply Voltage: 3.3V to 5V
* Interface: Digital
* Size:22x30mm

### Tutorial

#### Connection Diagram

![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005_2.png "Connection") 

#### Sample Code

    #define SensorLED   13
    //Connect the sensor to digital Pin 3 which is Interrupts 1.
    #define SensorINPUT  3  

    unsigned char state = 0;

    void setup() {
      pinMode(SensorLED, OUTPUT);
      pinMode(SensorINPUT, INPUT);
      //Trigger the blink function when the falling edge is detected
      attachInterrupt(1, blink, FALLING);  
    }

    void loop() {
      if (state != 0) {
        state = 0;
        digitalWrite(SensorLED, HIGH);
        delay(500);
      } 
      else
        digitalWrite(SensorLED, LOW);
    }

    //Interrupts function  
    void blink() {
        state++;
    }

#### Result
![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005.jpg "SENZ005") 

### Introduction

> What's the simplest way to check vibration with Arduino? Just vibrate this sensor,it is designed by PCBWay team and FizzyStudio team. Arduino can receive a digital signal. It's easy to acount and program in Arduino.
> Despite it's simple, you can make full use of it with creative thinking, like step counting, Crash warning light and so on.

### Specification

* Wide voltage range from 3.3V to 5V
* Standard assembling structure (two 3mm diameter holes with multiple of 5mm as distance from center)
* Easily recognitive interfaces of sensors ("A" for analog and "D" for digital)
* Icons to simplely illustrate sensor function
* High quality connector
* Immersion gold surface
* IO Type: Digital
* Switch life: up to 10 million seconds
* Open circuit resistance: 10Mohm
* Supply Voltage: 3.3V to 5V
* Interface: Digital
* Size:22x30mm

### Tutorial

#### Connection Diagram

![](https://github.com/FizzyStudio/SENZ005-Digital-Vibration-Sensor/blob/master/pic/SENZ005_2.png "Connection") 

#### Sample Code

    #define SensorLED   13
    //Connect the sensor to digital Pin 3 which is Interrupts 1.
    #define SensorINPUT  3  

    unsigned char state = 0;

    void setup() {
      pinMode(SensorLED, OUTPUT);
      pinMode(SensorINPUT, INPUT);
      //Trigger the blink function when the falling edge is detected
      attachInterrupt(1, blink, FALLING);  
    }

    void loop() {
      if (state != 0) {
        state = 0;
        digitalWrite(SensorLED, HIGH);
        delay(500);
      } 
      else
        digitalWrite(SensorLED, LOW);
    }

    //Interrupts function  
    void blink() {
        state++;
    }

#### Result
> As shown in figure connection , plug LED and lay a finger on Digital Vibration Sensor , LED will be lightened
