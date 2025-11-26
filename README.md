# Flyback Transformer Arc Generator

This project is a MOSFET-switched flyback transformer system designed to generate high-voltage arcs from a low-voltage DC power source. A battery supply is rapidly switched through the flyback primary using an NMOS transistor, creating high-voltage output capable of sustaining an air-gap arc.

**Purpose**: 
Utilize safe low voltage switching to manipulate and control high voltage environments.

**Resources**:
- 7.4V battery source (2 series 21700 50E batteries)
- Fast-blow fuse for input protection
- Push-button switch for manual enable
- Zener diode gate protection
- NMOS transistor for switching
- Snubber and timing capacitors
- Packaged flyback transformer
- Spark gap as the load

**Risks**: 
The flyback converter boosts voltages up to 400kV from a lower source. This amount of voltage can cause trama or even death if touched directly. It is important to never be near the arc when its active and to have the electrodes close to each other when activating the device.
