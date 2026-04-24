# Programming Digital Twins

## Lab Module 07 README.md

Be sure to implement all the requirements listed at [PDT-INF-07-001 - Lab Module 07](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/15).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This module implements multiple digital twin assets in one DTA instance. A second EDA instance has been simulated, which has been connected to a second thermostat digital twin asset in the scene. Color indication of temperature has been added to the cube object added to the thermostat controllers in module 6. The color of the cubes changes to visually indicate temperature to the user. Threshold events have been implemented, which send actuation commands to the thermostat EDAs when temperatures cross thresholds above or below the temperature set in the scene by the user using the interactive controls on the thermostat panels.

How does your implementation work?
The second digital twin asset is another instance of the thermostatControlAssembly, again mounted in the world to a cube object. Once the scene has started and connection is established to the broker, the user can provision the thermostat digitalTwinStateManagers to their respective EDA instance using their respective UI panels. A script has been added to the thermostatControlAssembly prefabs that ingests the temperature telemetry data and changes the base material color of the cube proportionally to the temperature value. This script is wired to the animation listener list of the digitalTwinStateHandler script on the thermostat controller. Another script has been added which triggers threshold events when the values exceed a set band around the desired temperature. This script is also wired to the animation listeners, and triggers actuatorCommand messages to be published to the broker, which are then interpreted by the EDAs and affect the generation of new simulated data.

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
