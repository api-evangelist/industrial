# Industrial (industrial)
An index and topic collection covering industrial APIs across industrial IoT (IIoT), operational technology (OT), SCADA, manufacturing, smart factory, asset management, predictive maintenance, energy management, and building automation. This collection profiles industrial cloud platforms (Siemens MindSphere, PTC ThingWorx, AWS IoT SiteWise, AWS IoT TwinMaker, AWS IoT Greengrass, Bosch IoT), historians and asset performance management tools (OSIsoft PI, AspenTech), edge and connector platforms (Litmus, Node-RED, HiveMQ, Aklivity), and the broader ecosystem of automation vendors (Rockwell Automation, Honeywell, Emerson, Schneider Electric) that expose APIs for plant data, equipment telemetry, work orders, and production runs. It anchors the OPC UA, MQTT Sparkplug B, and Modbus protocol family alongside the asset registry, telemetry, maintenance, and production data models that underpin modern industrial integration.

**URL:** [https://apievangelist.com](https://apievangelist.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Industrial IoT, Manufacturing, OT, SCADA, Asset Management, Edge, Predictive Maintenance, Energy Management, Smart Factory

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Asset Schema](https://raw.githubusercontent.com/api-evangelist/industrial/refs/heads/main/json-schema/industrial-asset-schema.json)
- [JSONSchema - Telemetry Reading Schema](https://raw.githubusercontent.com/api-evangelist/industrial/refs/heads/main/json-schema/industrial-telemetry-reading-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/industrial/refs/heads/main/json-ld/industrial-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/industrial/refs/heads/main/vocabulary/industrial-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Asset and Equipment Registries | Industrial APIs expose hierarchical asset models for plants, lines, machines, and components, enabling normalized identification and tagging across SCADA, MES, and ERP systems. |
| Telemetry Ingestion and Time-Series Storage | Platforms like AWS IoT SiteWise, Amazon Timestream, and OSIsoft PI ingest high-frequency sensor readings from PLCs, gateways, and historians through query and streaming APIs. |
| OPC UA, MQTT, and Sparkplug B Connectivity | Edge gateways and brokers (Litmus, HiveMQ, Aklivity, AWS IoT Greengrass) bridge OT protocols such as OPC UA, MQTT Sparkplug B, and Modbus into cloud-native API surfaces. |
| Predictive Maintenance and Anomaly Detection | Services like Amazon Lookout for Equipment and Amazon Monitron apply ML to vibration, temperature, and current signals to predict failures and surface work orders. |
| Digital Twins and 3D Operational Context | AWS IoT TwinMaker, Siemens MindSphere, and PTC ThingWorx assemble digital twin graphs that combine telemetry, 3D scenes, and asset metadata into queryable APIs. |
| Production Runs and Manufacturing Execution | APIs expose work orders, production runs, batch records, OEE, and quality events to coordinate MES, ERP, and shop-floor systems. |
| Energy and Building Automation | Schneider Electric, Honeywell, and Emerson APIs expose meter readings, HVAC controls, and energy-management workflows for industrial and commercial facilities. |
| Edge Compute and Local Orchestration | AWS IoT Greengrass, Node-RED, and Litmus run containers and flows on industrial gateways, exposing local APIs for protocol translation, store-and-forward, and on-device analytics. |

## Use Cases

| Name | Description |
|------|-------------|
| Plant-Wide Asset Performance Management | Operators unify asset data from OSIsoft PI, AWS IoT SiteWise, and AspenTech into APIs that power dashboards, reliability programs, and condition-based maintenance. |
| Predictive Maintenance for Rotating Equipment | Vibration and current data from pumps, motors, and compressors flows through Amazon Lookout for Equipment or Amazon Monitron APIs to predict failures and trigger CMMS work orders. |
| OPC UA to Cloud Telemetry Pipelines | Manufacturers use Litmus, AWS IoT Greengrass, or HiveMQ to map OPC UA tags to MQTT Sparkplug B and stream normalized telemetry through cloud APIs. |
| Manufacturing Execution and OEE | APIs from PTC ThingWorx, Rockwell FactoryTalk, and Siemens MindSphere expose production runs, downtime events, and OEE metrics to MES dashboards and ERP work-order systems. |
| Energy Management and Sustainability Reporting | Schneider Electric and Honeywell APIs aggregate sub-meter, HVAC, and process-energy data into normalized feeds for sustainability and carbon-reporting platforms. |
| Digital Twin Operations | AWS IoT TwinMaker, Siemens MindSphere, and PTC ThingWorx APIs combine 3D scenes, asset hierarchies, and live telemetry for remote operations, training, and root-cause analysis. |
| Industrial Data Historian Modernization | Operators expose decades of PI System and AspenTech historian data through cloud APIs to power machine learning, anomaly detection, and process-optimization workflows. |
| Edge Protocol Translation | Edge platforms like Litmus and Node-RED ingest Modbus, EtherNet/IP, and serial protocols at the gateway and republish them as MQTT, OPC UA, or REST APIs. |

## Integrations

| Name | Description |
|------|-------------|
| AWS IoT SiteWise | Managed industrial data service that collects, organizes, and analyzes equipment telemetry with hierarchical asset models and time-series APIs. |
| AWS IoT TwinMaker | Digital twin service that combines 3D scenes, real-time data, and entity-relationship graphs into APIs for industrial operations. |
| AWS IoT Greengrass | Edge runtime that runs Lambda functions, ML models, and connectors on industrial gateways with local APIs for protocol translation and store-and-forward. |
| Siemens MindSphere | Industrial IoT cloud platform that connects machines and physical infrastructure to APIs for asset management, fleet analytics, and predictive services. |
| PTC ThingWorx | Industrial IoT platform with APIs for asset modeling, mashups, augmented-reality work instructions, and manufacturing analytics. |
| OSIsoft PI System | De-facto industrial data historian with PI Web API endpoints for streaming, querying, and contextualizing decades of process and equipment data. |
| Litmus Automation | Industrial edge platform that connects PLCs, OPC UA servers, and MQTT brokers and exposes normalized data through cloud APIs. |
| HiveMQ | Enterprise MQTT broker widely used in industrial deployments for Sparkplug B telemetry, device management, and edge-to-cloud messaging. |

## Artifacts

Machine-readable industrial API specifications organized by format.

### JSON Schema

- [Asset Schema](json-schema/industrial-asset-schema.json)
- [Telemetry Reading Schema](json-schema/industrial-telemetry-reading-schema.json)

### JSON Structure

- [Asset Structure](json-structure/industrial-asset-structure.json)
- [Telemetry Reading Structure](json-structure/industrial-telemetry-reading-structure.json)

### JSON-LD

- [Industrial Context](json-ld/industrial-context.jsonld)

## Vocabulary

- [Industrial Vocabulary](vocabulary/industrial-vocabulary.yaml) — Unified taxonomy covering industrial assets, telemetry, maintenance orders, production runs, and the IIoT, OT, and MES domains.

## Network

This index references the following industrial API repositories:

- [1Factory](https://github.com/api-evangelist/1factory)
- [Aklivity](https://github.com/api-evangelist/aklivity)
- [Amazon FreeRTOS](https://github.com/api-evangelist/amazon-freertos)
- [Amazon IoT Core](https://github.com/api-evangelist/amazon-iot-core)
- [Amazon IoT Device Defender](https://github.com/api-evangelist/amazon-iot-device-defender)
- [Amazon IoT Device Management](https://github.com/api-evangelist/amazon-iot-device-management)
- [Amazon IoT Events](https://github.com/api-evangelist/amazon-iot-events)
- [Amazon IoT FleetWise](https://github.com/api-evangelist/amazon-iot-fleetwise)
- [Amazon IoT Greengrass](https://github.com/api-evangelist/amazon-iot-greengrass)
- [Amazon IoT SiteWise](https://github.com/api-evangelist/amazon-iot-sitewise)
- [Amazon IoT TwinMaker](https://github.com/api-evangelist/amazon-iot-twinmaker)
- [Amazon Lookout for Equipment](https://github.com/api-evangelist/amazon-lookout-for-equipment)
- [Amazon Monitron](https://github.com/api-evangelist/amazon-monitron)
- [Amazon Timestream](https://github.com/api-evangelist/amazon-timestream)
- [Apache NiFi](https://github.com/api-evangelist/apache-nifi)
- [Applied Materials](https://github.com/api-evangelist/applied-materials)
- [AspenTech](https://github.com/api-evangelist/aspentech)
- [Autodesk](https://github.com/api-evangelist/autodesk)
- [Baker Hughes](https://github.com/api-evangelist/baker-hughes)
- [Belden](https://github.com/api-evangelist/belden)
- [Bosch](https://github.com/api-evangelist/bosch)
- [Emerson Electric](https://github.com/api-evangelist/emerson-electric)
- [HiveMQ](https://github.com/api-evangelist/hivemq)
- [Honeywell](https://github.com/api-evangelist/honeywell)
- [Litmus](https://github.com/api-evangelist/litmus)
- [MQTT](https://github.com/api-evangelist/mqtt)
- [Node-RED](https://github.com/api-evangelist/node-red)
- [OSIsoft PI](https://github.com/api-evangelist/osisoft-pi)
- [PTC ThingWorx](https://github.com/api-evangelist/ptc-thingworx)
- [Rockwell Automation](https://github.com/api-evangelist/rockwell-automation)
- [Rockwell FactoryTalk](https://github.com/api-evangelist/rockwell-factorytalk)
- [Schneider Electric Exchange](https://github.com/api-evangelist/schneider-electric-exchange)
- [Siemens MindSphere](https://github.com/api-evangelist/siemens-mindsphere)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
