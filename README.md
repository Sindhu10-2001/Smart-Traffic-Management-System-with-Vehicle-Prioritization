This project presents an intelligent traffic control system integrating STM32F411RE, ESP32, IR sensors, GPS, and LoRa communication to optimize traffic flow and prioritize emergency vehicles.
IR sensors installed on each lane monitor real-time vehicle density, enabling dynamic adjustment of traffic signal timings. 
In emergency scenarios, vehicles such as ambulances and fire trucks are equipped with GPS and LoRa modules to transmit their location to the traffic controller. 
The system calculates the distance between the emergency vehicle and the intersection to determine the optimal green signal activation time.
A priority hierarchy is implemented, granting ambulances higher priority over fire trucks to ensure critical medical emergencies receive immediate clearance. 
Once the emergency vehicle has passed, the system seamlessly reverts to normal automated traffic management, enhancing road efficiency and emergency response times.
