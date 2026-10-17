# Garage Gate Controller

My teammate and I developed this university IoT project together. We used ESPHome and an ESP32 to create a garage and yard gate control prototype with Home Assistant integration.

## Collaboration and authorship
We collaborated on this project, and this repository presents our shared prototype. I contributed as a team member; the code, configuration and system design are our joint work, with contributions from both of us.

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
Our project is a university prototype. The original MQTT options and GPIO37/38/39 assignments require verification for the chosen ESP32 board and ESPHome version. The configuration has not been tested on hardware as part of this upload preparation.
