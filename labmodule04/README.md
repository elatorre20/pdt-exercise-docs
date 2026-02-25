# Programming Digital Twins

## Lab Module 04 README.md

Be sure to implement all the requirements listed at [PDT-INF-04-001 - Lab Module 04](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/12).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This module implements MQTT communication between the EDA and DTA.

How does your implementation work?
The EDA connects to an MQTT broker and publishes sensor messages in the specified format to the specified topic. The DigitalTwinManager component in the DTA connects to the MQTT broker and subscribes to these topics. The DigitalTwinManager then updates provisioned digital assets in the DTA as new messages come in.

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
