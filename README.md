# SmartOven
Make smart your oven!

The project consists in making a traditional kitchen oven smart, also usable remotely. The main functions concern: 
- The cooking programs that can be performed.
- Continuous monitoring of the current situation of the furnace.
- Run commands through Google Assistant to improve the user experience.
### Description
**Hardware requirements:** ESP32, three thermocouple sensors for high temperatures with MAX6675 module, one ds18b20 sensor, buzzer, six relays (one controls the power, four resistors and fan), one buzzer.

**Main tasks** inside the project: sensors, WebServer, SendInfo, SoundBuzzer, Display. (Semaphores / Mutex / Synchronization using **FreeRtos**)

**Languages:** C / C++ / Python

### Hardware scheme
![alt text](https://github.com/FerriZiniProjects/SmartOven/blob/main/scheme.jpg)

### MQTT scheme
![alt text](https://github.com/FerriZiniProjects/SmartOven/blob/main/MqttScheme.png)

For further information please contact the owner.
