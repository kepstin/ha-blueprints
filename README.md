# Home Assistant Blueprints

A collection of blueprints that I've written. Unless otherwise noted, blueprints are available under the terms of the [MIT License](COPYING).

## IKEA Controller Blueprints for ZHA

This is a collection of blueprints for IKEA Zigbee controllers used through the ZHA integration in Home Assistant. These blueprints are compatible with the [Awesome HA Blueprints Controllers-Hooks Ecosystem](https://epmatt.github.io/awesome-ha-blueprints/docs/controllers-hooks-ecosystem).

The reason that these controller blueprints exist is to support controller features that have been added in newer firmware versions (such as native double-press events), simplify the code by only supporting a single Zigbee integration, and fix some bugs in the event handling.

### IKEA E1812 TRÅDFRI Shortcut Button (ZHA, firmware 24.x.x)

Run actions on single presses, double presses, and long presses and releases of the TRÅDFRI Shortcut Button. Optionally, an action can be looped while the button is held. This blueprint uses the device native support support for double presses, which requires firmware version 24.x.x. It does not require an `input_text` helper.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fkepstin%2Fha-blueprints%2Fblob%2Fmain%2Fautomation%2Fikea_e1812_zha.yaml)

Version: 1.0.0
