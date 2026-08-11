# FooDron — Quadcopter Engineering Project

**Design, assembly, electronic integration and flight testing of a custom quadcopter prototype developed to explore food delivery for elderly people and users with reduced mobility.**

![FooDron final prototype](images/00-final-prototype-and-transmitter.jpg)

## Project Overview

FooDron is a personal engineering project built from individual mechanical and electronic components rather than from a ready-to-fly drone.

The project involved assembling the quadcopter frame, installing the propulsion system, soldering and integrating the power electronics, connecting the flight-control and radio systems, configuring the flight controller, integrating GPS and a remotely controlled payload-release mechanism, and carrying out progressive functional and flight tests.

The main objective was to develop a functional prototype capable of flying while exploring the concept of transporting a small payload for people with reduced mobility.

## Engineering Areas

- Mechanical assembly
- Brushless propulsion systems
- Electronic Speed Controllers (ESC)
- Power distribution and soldering
- Electrical wiring and connectors
- Radio control integration
- Flight-controller configuration
- GPS and compass integration
- ArduPilot / Mission Planner configuration
- Payload-release mechanism
- Troubleshooting and testing
- Iterative prototyping

## Main Components

- F450 quadcopter frame
- 4 × A2212 1000KV brushless motors
- 4 × 30A ESCs
- APM flight controller
- GPS module with compass
- FlySky radio transmitter and receiver
- Propellers
- Battery and power connections
- Remote-controlled payload-release system

## Build Process

### 1. Components and frame

The project began with the individual structural, propulsion and electronic components.

![Components overview](images/01-components-overview.jpg)

![F450 frame arms](images/02-f450-frame-arms.jpg)

### 2. Propulsion system

Four brushless motors and their corresponding ESCs were prepared for installation.

![Brushless motors](images/03-a2212-brushless-motors.jpg)

![30A ESCs](images/04-30a-escs.jpg)

### 3. Mechanical assembly

The motors were mounted onto the F450 arms and the mechanical structure was progressively assembled.

![Frame and motor installation](images/06-frame-and-motor-installation.jpg)

The complete build was carried out manually from the individual components.

![Manual assembly process](images/07-manual-assembly-process.jpg)

### 4. Power distribution and soldering

The electrical power connections were soldered to the distribution board before integrating the ESCs and the rest of the electronics.

![Power distribution soldering](images/08-power-distribution-soldering.jpg)

### 5. ESC and wiring integration

The four ESCs were installed and the motor, power and control wiring was routed through the quadcopter structure.

![ESC and wiring integration](images/09-esc-and-wiring-integration.jpg)

### 6. Electronics integration

The radio receiver, flight-control electronics and associated wiring were progressively incorporated into the platform.

![Electronics integration](images/10-electronics-integration.jpg)

The radio-control system uses a FlySky receiver.

![FlySky receiver](images/12-flysky-fs-ia6b-receiver.jpg)

### 7. Flight-controller configuration

The flight-control system was configured and calibrated using **ArduPilot / Mission Planner**, including compass-related configuration.

![ArduPilot Mission Planner calibration](images/13-ardupilot-mission-planner-compass-calibration.jpg)

### 8. Propeller installation and final assembly

After integration of the propulsion and control systems, the propellers were installed and the quadcopter reached its functional prototype configuration.

![Propeller installation](images/11-propeller-installation.jpg)

## Payload Release System

A remotely controlled payload-release mechanism was incorporated to explore the original food-delivery concept.

![Payload release mechanism](images/14-payload-release-mechanism.jpg)

![Payload release remote](images/15-payload-release-remote.jpg)

## Final Prototype

The completed prototype integrates the frame, propulsion system, flight electronics, GPS, radio-control system, battery and payload-related hardware.

![Final prototype top view](images/16-final-prototype-top-view.jpg)

## Testing and Validation

Testing was carried out progressively, from electronic and motor-response checks to complete flight tests.

### Radio and electronics test

[▶ Watch radio and electronics test](videos/03-radio-and-electronics-test.mp4)

### Motor response test

[▶ Watch motor response test](videos/04-motor-response-test.mp4)

### Initial flight test

[▶ Watch initial flight test](videos/01-initial-flight-test.mp4)

### Outdoor flight test

[▶ Watch outdoor flight test](videos/02-outdoor-flight-test.mp4)

The flight-testing stage demonstrated that the prototype was capable of taking off and flying. Testing also revealed aspects of flight behaviour and control that could be further refined in future iterations.

## Project Presentation

[▶ Watch project presentation](videos/05-project-presentation.mp4)

[▶ Watch final prototype walkaround](videos/06-final-prototype-walkaround.mp4)

## Technical Documentation

The original project report and supporting documentation are available in the [`docs`](docs/) folder.

## What I Learned

This project gave me practical experience in taking an engineering concept from individual components to a functioning physical prototype.

It required combining mechanical assembly, electronics, soldering, wiring, configuration, troubleshooting and real-world testing. The project also reinforced the importance of iterative development: assembling, testing, identifying problems and making improvements based on actual system behaviour.

## Future Improvements

Potential future development could include:

- Improved cable management and component packaging
- Further flight-controller tuning
- More systematic payload testing
- Weight-distribution optimisation
- Additional flight testing
- Improved landing behaviour
- Further development of the delivery mechanism

---

**Built as a personal engineering project by David Jorge Cobo.**
