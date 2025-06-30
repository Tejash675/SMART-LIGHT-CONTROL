# SMART-LIGHT-CONTROL
COMPANY : CODTECH IT SOLUTIONS

NAME : SINGAMPALLI TEJASH VARDHAN 

INTERN ID : CT04DF1943

DOMAIN : INTERNET OF THINGS

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH KUMAR

This project is a simulation of an Automatic Street Light System using an Arduino Uno, a Photoresistor (LDR), LEDs, and a breadboard, created and executed on the Tinkercad Circuits platform. The aim of the system is to automatically control street lights based on ambient light intensity—turning them ON during darkness and OFF during daylight—thus promoting energy efficiency and automation. The core of this system is the LDR (Light Dependent Resistor), which changes its resistance based on the intensity of surrounding light. As the light level decreases (at night), the resistance of the LDR increases, resulting in a lower voltage being read by the Arduino. Conversely, in bright light, the LDR resistance drops and the Arduino receives a higher analog voltage.

In this simulation, the Arduino Uno acts as the brain of the system. The LDR is connected to analog pin A0 of the Arduino through a voltage divider circuit made with a 10kΩ resistor. One end of the LDR is connected to the 5V power supply from the Arduino, while the other end is connected to A0 and also to the 10kΩ resistor, which then goes to ground (GND). This configuration allows the Arduino to sense the voltage changes due to varying light intensities. Two LEDs (one red and one blue) are used to represent the street lights. These are connected to digital pins 2 and 3 of the Arduino, respectively. Each LED is connected in series with a 220Ω resistor to limit the current and protect the LEDs from damage. The cathodes (shorter legs) of the LEDs are connected to the common ground.

The logic implemented in the Arduino code is straightforward. When the analog value read from the LDR is below a certain threshold (indicating low light or darkness), the Arduino sets the digital pins connected to the LEDs to HIGH, turning the LEDs ON. When the light level is sufficient (i.e., the LDR value goes above the threshold), the digital pins are set to LOW, turning the LEDs OFF. This simulates the behavior of automatic streetlights that function without manual intervention.

The entire circuit and code were designed and tested in Tinkercad, a free online platform by Autodesk that allows users to simulate electronics circuits virtually. Tinkercad provides a drag-and-drop interface to place components like Arduino, LEDs, resistors, and LDRs on a virtual breadboard. It also allows users to write and upload Arduino code and observe the output in real time. One of the useful features in Tinkercad is the LDR light slider, which simulates varying ambient light and helps test the circuit's response to different light levels.

This project not only introduces students to the fundamentals of sensor-based automation but also enhances understanding of analog input, digital output control, and real-world applications of embedded systems. It demonstrates how simple components can be used effectively to solve everyday problems, and how platforms like Tinkercad can make prototyping and learning accessible without needing physical hardware.

![Image](https://github.com/user-attachments/assets/511c0727-964e-416e-8ec7-214a7dd29c4e)
