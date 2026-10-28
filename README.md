# Density-Based Traffic Light Controller

Arduino prototype for two-lane traffic-light sequencing using two digital infrared sensors.

## What this repository demonstrates

Two IR inputs on pins 2 and 3; traffic LEDs on pins 4–9; conditional lane prioritization; timed green and yellow phases.

## Source code

Main example: `Density based traffic light controller.ino`.

## How to explore

Clone or download the repository, open the source file, and review its dependencies and hardware or dataset assumptions. Arduino sketches require the appropriate Arduino IDE board and libraries; Python scripts require the imports and referenced datasets; web exercises can be opened or adapted locally.

## Scope and limitations

The code assumes LOW means a vehicle is detected. The current implementation uses blocking delays and includes a zero-duration yellow phase in one path. It is a demonstration, not road-safe traffic-control software.

## Development notes

This repository is maintained as a learning or engineering prototype. Documented behavior is based on source-code inspection; this documentation does not claim independent hardware testing or performance validation.

## Security

Do not add personal data, private datasets, credentials, or API keys to public commits.
