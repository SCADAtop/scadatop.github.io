
# Welcome to SCADAtOP

**ScadaTop** is an open-source platform designed to simulate, integrate, and manage **industrial IoT (IIoT) and smart home applications**.
It provides a complete suite of containerized demo services that run seamlessly on **Raspberry Pi, Khadas boards, and other edge devices**, making it easy for developers, researchers, and educators to experiment with modern data pipelines.

With ScadaTop, you can:

* **Simulate industrial devices** with the `demo-suite.opcua-simulator`, which emulates OPC-UA servers commonly found in PLCs.
* **Bridge industrial data to MQTT** using the `demo-suite.mqtt-gateway`, which connects multiple OPC-UA clients, transforms messages, and publishes them to an MQTT broker.
* **Control data flows and security** through **Flow-Weaver**, a rule and policy management system for EMQX (rules, webhooks, authentication, authorization).
* **Clean and prepare time-series data** with the `demo-suite.pipeline-sanitizer`, a web service that processes webhook outputs from EMQX and stores sanitized data into a time-series database.

ScadaTop provides **ready-to-use Docker packages** for easy deployment and can be extended for different application scenarios.

### Example Scenarios

* **Agricultural IoT**: Monitor environmental factors (temperature, humidity, soil conditions) across farms, simulate sensor networks, and visualize data pipelines from field to cloud.
* **Home Automation**: Integrate with **HomeAssistant** to demonstrate smart home use cases, from device simulation to MQTT messaging and data processing.

By combining simulation, data transformation, and visualization in a modular architecture, **ScadaTop bridges the gap between industrial protocols and modern IoT ecosystems**.
