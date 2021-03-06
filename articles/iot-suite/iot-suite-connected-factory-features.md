---
title: Connected Factory solution features - Azure | Microsoft Docs
description: An overview of the features of the Connected Factory preconfigured solution.
services: iot-suite
suite: iot-suite
documentationcenter: ''
author: dominicbetts
manager: timlt
editor: ''

ms.assetid: 
ms.service: iot-suite
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 04/20/2018
ms.author: dobett

---
# What is Azure IoT Suite Connected Factory?

Connected Factory is an implementation of Microsoft's Azure Industrial IoT reference architecture, packaged as on open-source solution. You can use it as a starting point for a commercial product. You can deploy a pre-built version of the Connected Factory solution into your Azure subscription from [Azure IoT Suite](https://www.azureiotsuite.com/#solutions/types/CF).

![Connected Factory solution dashboard](media/iot-suite-connected-factory-features/dashboard.png)

Connected Factory includes the following features:

## Industrial device interoperability

- Connect to industrial assets with an OPC UA interface.
- Use the simulated production lines (running OPC UA servers in Docker containers) to see live telemetry from them.
- Browse the OPC UA information model of the OPC UA servers from a cloud dashboard.

## Remote management

- Configure your OPC UA assets from the cloud dashboard (call methods, read, and write data).
- Publish and unpublish telemetry data from your OPC UA assets from a cloud dashboard.

## Cloud dashboard

- View telemetry previews directly in a cloud dashboard.
- View trends in telemetry data and create correlations using the Time Series Insights Explorer dashboard.
- See calculated Overall Equipment Efficiency (OEE) and Key Performance Indicators (KPIs) from a cloud dashboard.
- View industrial asset hierarchies in a tree topology as well as on an interactive map.
- View, acknowledge, and close alerts from a cloud dashboard.

## Azure Time Series Insights

- [Azure Time Series Insights](../time-series-insights/time-series-insights-overview.md) is built for storing, visualizing, and querying large amounts of time-series data. Connected Factory leverages this service.
- Connected Factory integrates with this service enabling you perform deep, real-time analysis of your device data.

## Rules and alerts

[Configure threshold-based rules for alerts](iot-suite-connected-factory-configure.md).

## End-to-end security

- Configure security permissions for users using Role-Based Access Control (RBAC).
- End-to-end encryption is implemented using OPC UA authentication (using X.509 certificates) as well as security tokens.

## Customizability

- [Customize](iot-suite-v1-guidance-on-customizing-preconfigured-solutions.md) the solution to meet specific business requirements.
- Full solution source-code available on GitHub. See the [Connected Factory preconfigured solution](https://github.com/Azure/azure-iot-connected-factory) repository.

## Next steps

Learn more about the Connected Factory preconfigured solution by reading the following articles:

* [Connected Factory preconfigured solution walkthrough](iot-suite-connected-factory-sample-walkthrough.md)
* [Deploy a gateway for Connected Factory]( iot-suite-connected-factory-gateway-deployment.md)
