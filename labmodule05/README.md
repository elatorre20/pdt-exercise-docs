# Programming Digital Twins

## Lab Module 05 README.md

Be sure to implement all the requirements listed at [PDT-INF-05-001 - Lab Module 05](https://github.com/programming-digital-twins/pdt-exercise-tasks/issues/13).


### Description

INSTRUCTIONS: Describe, in your own words, the high-level functionality of this lab module by answering the questions listed below.

What does your implementation do? 
This module implements data integration between the EDA and DTA. In this module, provisioned virtual assets in the DTA change to reflect incoming data from the EDA. This module additionally implements LLM connectivity to the DTA.

How does your implementation work?
The EDA publishes messages in a specified format to specified topics on the MQTT broker. The DigitalTwinManager component of the DTA connects to the broker, subscribes to the topic, and exposes incoming messages to other game objects. The prefabs of digital assets such as PowerGenerationSystemController and ThermostatControlAssembly can be provisioned to specific EDA instances publishing to the broker. Once they have been provisioned, they handle incoming data by updating the DTA state to match. For instance, the ThermostatControlAssembly updates the displayed temperature to match the temperature published by the EDA. In the UI panel attached to each digital twin prefab, there is an additional flyout UI panel which controls the LLM integration. After establishing connection to a locally running Ollama integration, this panel allows the user to send queries to the model and displays its response.

### Design Diagram(s)

INSTRUCTIONS: Include one or more design diagram(s) representing your solution.


### Specific Features

INSTRUCTIONS: List the specific features implemented (or integrated) as part of this lab module. Preface each with either 'EDA' (for the Edge Device App) or 'DTA' (for the Digital Twin App). Keep each feature as concise as possible - e.g., 'EDA: Connects to MQTT broker' or 'DTA: Consumes EDA telemetry via MQTT'.

- 
- 
- 


EOF.
