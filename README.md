# Garage Gate Controller

University IoT project developed collaboratively by Paulina (@paulina-22) and a teammate: an ESPHome configuration for an ESP32 garage and yard gate control prototype with Home Assistant integration.

## Collaboration and authorship
This was a shared university project, not entirely Paulina's individual work. The repository presents the team's prototype; it does not claim that Paulina independently authored every part of the code, configuration or system design.

## Contents
- `garage-gate.yaml`: prototype configuration with GPIO inputs and switches.
- `secrets.example.yaml`: placeholder values showing the required secrets.

## Setup
1. Install ESPHome and check compatibility with your ESP32 hardware and ESPHome version.
2. Copy `secrets.example.yaml` to `secrets.yaml` and replace all placeholders locally.
3. Update the device address, MQTT broker, and pin mapping to suit your hardware.
4. Validate with `esphome config garage-gate.yaml` before compiling or flashing.

`secrets.yaml` is excluded from Git. Addresses in the configuration are documentation placeholders. No original passwords or encryption keys are included.

## Prototype limitations
This is a preserved university prototype, not a finished gate controller. The original MQTT options and GPIO37/38/39 assignments require verification for the chosen ESP32 board and ESPHome version. The configuration has not been tested on hardware as part of this upload preparation.
