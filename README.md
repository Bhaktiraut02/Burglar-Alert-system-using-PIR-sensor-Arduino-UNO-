# Burglar Alert system using PIR sensor Arduino UNO 
IoT Internship completion Mini project 
### Project Report
The project problem statement is **Create a burglar alarm – detect motion of a person (using a PIR sensor) and If there is motion, ring the buzzer (using Arduino UNO).**
### Components required for this project
- PIR sensor (Passive Infrared Sensor) 
- Arduino UNO board
- Buzzer
### Component Discription
- **PIR Senosor:** It is a special type of sensor which is usually used for security purposes. It detects the objects by reading the Infrared radiations emitted by the objects. Any object whose temperature is above absolute zero, emits radiation.
This radiation is not visible to human eyes. The PIR sensor is designed to detect this Infrared radiation. A PIR motion sensor has a pair of pyro electric sensors to detect heat energy from the
surrounding environment. It helps generate an electrical signal when they are heated or cooled.

<img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/pir.jpg" width="300"/> <img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/pir2.jpg" width="500"/>

- **Arduino UNO:** Arduino is an open-source platform used for building electronics projects. Arduino consists of both a physical programmable circuit board (often referred to as a microcontroller) and a
piece of software, or IDE (Integrated Development Environment) that runs on your computer, used to write and upload computer code to the physical board.
The Arduino platform has become quite popular with people just starting out with electronics, and for good reason. Unlike most previous programmable circuit boards, the Arduino does
not need a separate piece of hardware (called a programmer) in order to load new code onto the board -- you can simply use a USB cable. Additionally, the Arduino IDE uses a simplified
version of C++, making it easier to learn to program. Finally, Arduino provides a standard form factor that breaks out the functions of the micro-controller into a more accessible
package.
<img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/uno.png" width="600" height= "400"/>

------------

### The project has been completed and simulated over Tinkercad:
The connections and simualation for the same are as follows:

<img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/1.png" />
<img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/2.png" />

If the motion is detected within the range of the PIR sensor those fluctuations in IR will be detected and then a HIGH will be sent to the sensor and the buzzer will be triggered, alarming us of the unnecessary movement in restricted areas.
The code for the simualtion to work successfully is developed over Arduino IDE

<img align="center" alt="GIF" src="https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/4.png" />

## Conclusion
We can observe from the simulations above that when the object is moved or some motion is generated then quickly the PIR sensor detects it and sets the buzzer on, alarming us of the motion detected. There is a delay of 100 ms in between the movement being detected and the next movement. This is the basic prototype of how large scale security devices work and can be used in our day to day households as a Burglar alarm system.  
We learnt the basic hardware and pin configurations of Arduino UNO and how it can be configured with sensors, etc. We gained a sufficient knowledge of how to develop the code over Arduino IDE. We have successfully designed a burglar alarm system using PIR sensor and Arduino UNO. 

------------

### The detailed Final Project Reoprt can be found attached below:
[Final Project Report: Creating a Burglar alarm system using PIR sensor and Arduino UNO](https://github.com/Bhaktiraut02/Burglar-Alert-system-using-PIR-sensor-Arduino-UNO-/blob/main/Bhakti%20Raut_MiniProject_IOT_PIR%20Sensor.pdf)
