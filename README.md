# MOSFET H-Bridge Motor Driver

A discrete MOSFET based H-Bridge driver for DC motors.

## Features
- Motor voltage: 6V – 24V
- Current: up to 10A (depends on MOSFET)
- Simple design
- Logic level control

## Hardware
Components used:
- 2x P-channel MOSFET
- 2x N-channel MOSFET
- Gate resistors
- Pull-down/up resistors
- 4x6N137 High speed optocoupler

## Schematic
[Schematic PDF](images/Schematic.pdf)

## BOM
| Component | Value |
|-----------|------|
| MOSFET | IRLZ44N |
| MOSFET | IRF4905 |
| R1 | 10k |
| R2 | 100Ω |

## License
MIT License
