# VLSI-Four-Way-Traffic-System-Using-Verilog

## About

The main objective of this project is to design a Four Way Traffic Light Signal that allows passage through one road of an intersection at a time, while denying passage on the other three roads. Additionally, the system will account for three different scenarios: presence of emergency vehicles, presence of traffic jams and density of traffic.

Four roads are to be considered: North, South, East and West. Each road has a traffic light capable of displaying Red, Yellow and Green lights, along with a sensor to allow preferential sequencing of the traffic lights. The light will turn Green in a circular manner, that is, North-West-South-East. The rate at which the lights change color will be fixed to 20s for Green and 4s for Yellow, so that drivers and pedestrians can plan out if there is enough time to attempt to cross the intersection. The sensors will provide output based on the following scenarios: presence of emergency vehicles, presence of traffic jams and density of traffic. If any emergency vehicles are detected on a road, the traffic light should immediately change to Green to allow them to pass through. If there is traffic on a certain road, the light will turn Green to prevent gridlock on that road. And if a road is empty while the traffic light is Green, the light will change to Yellow to prevent any vehicular collision. The emergency condition will be checked first as it has the highest priority, followed by traffic jam condition, and lastly, empty condition.

The code has been verified using ***Cadence Testbench***.
