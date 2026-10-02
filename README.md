# Roof Inspection Drone Image Geotagging

Build a drones prototype that uses barometer to associate captured images with coordinates. Include setup instructions, a circuit diagram, tested firmware, and sample output.

> Build and test at safe low voltage. Real machinery, vehicles, aircraft, pumps, and power systems require qualified engineering review and certified safeguards.

## Project details

| Field | Value |
| --- | --- |
| Roadmap ID | 844 |
| Category | Drones |
| Platform | ESP32 |
| Difficulty | Intermediate |
| Estimated build time | 32 hours |
| Connectivity | MAVLink |
| Core components | barometer |
| Control mode | edge classification |

## Repository layout

- `firmware/roof-inspection-drone-image-geotagging/roof-inspection-drone-image-geotagging.ino`: runnable firmware or application
- `docs/wiring.md`: suggested low-voltage wiring plan
- `docs/architecture.md`: system data flow
- `docs/test-plan.md`: repeatable verification steps
- `sample-data/example.json`: example telemetry record
- `tools/validate.py`: dependency-free repository validation

## Quick start

1. Open `firmware/roof-inspection-drone-image-geotagging/roof-inspection-drone-image-geotagging.ino` in Arduino IDE or Arduino CLI.
2. Select the board matching **ESP32**.
3. Compile and upload, then open the serial monitor at 115200 baud.

## Expected behavior

Image Geotagging demonstration with repeatable test steps. The default implementation supports simulated or generic analog inputs so the control path can be exercised before hardware-specific drivers are added.

## Hardware adaptation

The included code is a safe reference implementation. Update pin assignments and sensor conversions from the exact component datasheets, then repeat the test plan before connecting actuators.

## License

MIT
