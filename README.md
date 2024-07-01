# Voltix Module Hardware Design Files

[![Kibot ERC/DRC](https://github.com/VoltixTeam/Voltix_Module/actions/workflows/test.yml/badge.svg)](https://github.com/VoltixTeam/Voltix_Module/actions/workflows/test.yml)

The Voltix Module is a stamp-sized unit (27.2mm by 15.2mm) that can be soldered onto a user's \ac{pcb} with additional circuitry like sensors or harvesters to create deployment-ready battery-free devices quickly.
It integrates harvesting circuitry, two MCUs, an RTC, a PCB antenna, and an LED on a compact 4-layer PCB enclosed in a metal RF shield.
The module features breadboard-compatible castellated holes exposing essential signals, including 11 GPIO, two of which can also function as analog inputs.
Four additional signals on the back of the module are available when reflow-soldered onto a carrier board.

For more details and pinouts, refer to the [documentation](https://voltix-docs.vercel.app/hardware/module.html).

Latest design files:
 - [Schematics](https://voltix-docs.vercel.app/artifacts/module/latest/schematics.pdf)
 - [Layout](https://voltix-docs.vercel.app/artifacts/module/latest/pcb.pdf)
 - [3D rendering](https://voltix-docs.vercel.app/artifacts/module/latest/3drendering.png)
 - [3D step model](./resources/VoltixModule.step)
 - [Kicad schematic symbol](./resources/VoltixModule.kicad_sym)
 - [Kicad footprint](./resources/VoltixModule.pretty)

![Rendering of Voltix module](https://voltix-docs.vercel.app/artifacts/module/latest/3drendering.png "Voltix module")
