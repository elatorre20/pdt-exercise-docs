# Programming Digital Twins

## Lab Module 06 README.md

Be sure to implement all the requirements listed at [PDT-INF-06-001 - Lab Module 06](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/14).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This model implements various interaction components which display information from the digital twin to the user. The HUD components allow the user to set up and monitor the state of the DTA's connection to the broker, and each digital twin asset has an individual HUD to control provisioning. A thermostat assembly is included as an example digital twin asset, with an interactible panel displaying temperature to the user and allowing command input.

How does your implementation work?
Several of the labbenchstudios prefabs are used in this module. DigitalTwinManager subcomponent DigitalTwinHudContainer contains the 2d UI panels that control connection to the broker. Each digital twin asset has a DigitalTwinStateManager prefab that controls the model parsing and provisioning of that specific asset. The ThermostatControlAssembly contains the displays and interaction buttons for the thermostat digital twin asset. When provisioned to an EDA instance with the thermostat type, it processes telemetry updates and pushes them to the display, as well as processing commands from the display and pushing them to the EDA instance.

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
