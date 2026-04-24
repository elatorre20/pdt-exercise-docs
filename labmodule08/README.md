# Programming Digital Twins

## Lab Module 08 README.md

Be sure to implement all the requirements listed at [PDT-INF-08-001 - Lab Module 08](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/16).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This module implements predictive maintenance functionality to the DTA. A new digital twin asset representing a wind turbine power generation system has been added, along with a matching EDA instance generating simulated data.

How does your implementation work?
The powerGenerationSystem prefab contains a digital twin asset of the wind turbine and associated components. By disabling the braking feature of the prefab, it is possible to view operation outside the nominal range of the wind turbine. This can then be used to estimate the RUL of the turbine by keeping track of the number of cycles overspeed and feeding them into an SN-curve. 

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
