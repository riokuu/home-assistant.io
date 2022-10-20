---
title: BleBox devices
description: Instructions on how to integrate BleBox devices with Home Assistant.
ha_category:
  - Cover
ha_release: '0.110'
ha_iot_class: Local Polling
ha_config_flow: true
ha_codeowners:
  - '@bbx-a'
  - '@riokuu'
ha_domain: blebox
ha_platforms:
  - air_quality
  - button
  - climate
  - cover
  - light
  - sensor
  - switch
ha_integration_type: integration
---

[BleBox](https://blebox.eu/?lang=en) produces small, low-power, surprisingly affordable, feature-rich WiFi devices for serverless home automation.

{% include integrations/config_flow.md %}

For the best experience, make sure your BleBox devices have the most recent available firmware installed.

Additionally, if you are configuring a gateBox, it may be useful to set the second button as "stop" in your device's settings (via website or phone app).

## Covers

This integration adds the BleBox device as a cover in Home Assistant.

Currently, this includes support for the following product classes:

- BleBox shutterBox
- BleBox rollerGate
- BleBox gateBox

For now, only a minimum set of features are supported (e.g., no tilt support for shutterBox).
## Binary sensors
This integration adds BleBox device as a binary_sensor in Home Assistant.

Currently, this includes support for the following product classes:

- BleBox rainSensor
- BleBox wind&rainSensor (rain only)
## Sensors

This integration adds the BleBox device as a sensor in Home Assistant.

Currently, this includes support for the following product classes and their features:

- BleBox tempSensor (temperature only)

## Switches

This integration adds the BleBox device as a switch (or multiple switches) in Home Assistant.

Currently, this includes support for the following product classes:

- BleBox switchBox
- BleBox switchBoxD

## Climate

This integration adds the BleBox device as a climate in Home Assistant.

Currently, this includes support for the following product classes:

- BleBox saunaBox

## Air Quality

This integration adds the BleBox device as an air quality entity in Home Assistant.

Currently, this includes support for the following product classes:

- BleBox airSensor

## Lights

This integration adds the BleBox device as a light in Home Assistant.

Currently, the following product classes are supported:

- BleBox dimmerBox
- BleBox wLightBoxS
- BleBox wLightBox

## Button

This integration adds the BleBox device as a button in Home Assistant

Currently, this includes support for the following product classes:

- BleBox tvLiftBox
