# Programming Digital Twins

## Lab Module 09 README.md

Be sure to implement all the requirements listed at [PDT-INF-09-001 - Lab Module 09](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/17).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This module implements user training through historical data capture and replay in the DTA. The data historian stores incoming telemetry representing conditions in the EDA in which users need to be trained. The data can then be replayed in the DTA, allowing the user to experience this situation without any connection to real hardware and to practice implementing appropriate responses. 


How does your implementation work?
The printer simulation described further in module 10 was recorded using simulated data from the mqtt bridge script in simulation mode. The simulation was set to raise the printer temperature to a non-optimal temperature during printing operation. When this data is replayed, the trainee user is expected to send a command correcting the nozzle temperature within a timely fashion. 

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
