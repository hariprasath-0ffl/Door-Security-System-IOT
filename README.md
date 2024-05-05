DESCRIPTION 

Door security systems have revolutionized home safety by integrating IoT technologies, sensors, and smart locks to monitor and manage access. These systems use real-time data collection and analysis to detect motion, unauthorized access, and door status. The data is processed through algorithms and machine learning, providing actionable insights for proactive security measures and automated door management. Remote monitoring and control via mobile apps or web interfaces allow homeowners to manage door locks, view live camera feeds, and receive notifications from anywhere. Door security systems are scalable and adaptable, easily integrating additional devices for comprehensive protection. Compatibility with other smart home technologies enables seamless automation and a more interconnected living experience. Overall, these systems offer enhanced security, control, and convenience, making homes safer and more efficient.

COMPONENTS

**IR Sensor:**

![download](https://github.com/hariprasath-0ffl/Door-Security-System-IOT/assets/123928482/ffe89b72-94d8-4cc2-8d4c-4291629abf95)

1. **Principle:** Uses infrared light to detect objects and measure distances.
2. **Components:** Consists of an IR transmitter (LED) and an IR receiver (photodiode).
4. **Functionality:** Emits infrared light, which reflects off objects and is detected by the receiver, allowing distance calculation.
5. **Applications:** Used in proximity sensing, obstacle detection, and line following in robotics and automation.
6. **Interfacing:** Can be easily connected to Arduino and other microcontrollers for data processing and control.

**Arduino Uno Board:**


![arduino-uno-smd-1000x1000](https://github.com/hariprasath-0ffl/Door-Security-System-IOT/assets/123928482/039b7418-4195-4fc6-9104-15969e922cab)

1. **Microcontroller:** Uses the ATmega328P microcontroller, providing digital and analog I/O pins.
2. **Features:** Offers easy programming through the Arduino IDE and USB connectivity for power and data transfer.
3. **Compatibility:** Works with a wide range of sensors, actuators, and shields, making it versatile for various projects.
4. **Open-Source:** Based on open-source hardware and software, allowing for community-driven improvements and libraries.
5. **Cost-Effective:** Relatively inexpensive compared to other microcontroller boards, making it ideal for beginners and prototyping.

**Buzzer:**


![download](https://github.com/hariprasath-0ffl/Door-Security-System-IOT/assets/123928482/def075a2-1966-4746-a8cc-ae05754bb91e)

1. **Function:** Produces sound or tone when a voltage is applied, often used for alarms, notifications, or simple melodies.
2. **Types:** Available in active and passive types, with active buzzers having an internal oscillator to produce sound.
3. **Operating Voltage:** Typically operates at low voltages (e.g., 3-5V), making it suitable for use with microcontrollers like Arduino.
4. **Control:** Can be controlled using PWM (Pulse Width Modulation) to generate different tones or adjust the volume.
5. **Applications:** Used in alarm systems, timers, musical instruments, and various electronic projects requiring audio feedback.

 WORKING


![Door-security-System circuit](https://github.com/hariprasath-0ffl/Door-Security-System-IOT/assets/123928482/6cb205a2-b8c7-40de-a1a6-2c9e66561f2a)
1. **IR Sensor Emission:** The IR sensor emits infrared light from its IR transmitter.
2. **Object Interaction:** When an object comes in the path of this emitted light, it reflects some of it back towards the IR receiver.
3. **Receiver Detection:** The IR receiver detects this reflected light.
4. **Arduino Interface:** The IR sensor is connected to the Arduino Uno board.
5. **Analog Input:** The Arduino Uno reads the analog signal from the IR sensor, which varies based on the distance of the object.
6. **Distance Calculation:** Using the analog signal, the Arduino calculates the distance of the object from the sensor.
![photo_2024-05-03_07-47-00](https://github.com/hariprasath-0ffl/Door-Security-System-IOT/assets/123928482/b0ef5805-e6b5-4370-b413-0fdd5f1a4761)

   
8. **Threshold Setup:** A threshold distance is set in the Arduino code to trigger an action (e.g., activating the buzzer).
9. **Conditional Statement:** If the calculated distance is less than the threshold, the Arduino activates the buzzer.
10. **Buzzer Activation:** The Arduino sends a signal to the buzzer to produce a sound.
11. **Sound Frequency:** The frequency of the sound produced by the buzzer can be controlled by the Arduino.
12. **Feedback Signal:** This sound serves as a feedback signal indicating the proximity of an object.
13. **Continuous Monitoring:** The Arduino continuously monitors the IR sensor's readings and adjusts the buzzer's activation based on the distance.
14. **Alarm System:** This setup can be used as a simple alarm system, alerting when an object comes too close to the sensor.
15. **Feedback Mechanism:** The buzzer's sound provides immediate feedback without the need for visual monitoring.
16. **Versatile Application:** This system can be applied in various scenarios such as security systems, obstacle detection, or interactive installations.
 
