# ExtraICE4

ExtraICE4 is a competition robot called Micromouse.

For more information on Micromouse competitions, please see the [website](https://www.ntf.or.jp/) of the New Technology Foundation.

## Hardware

- 3DCAD data by Fusion360 : https://t.co/qPmjVBnEnc
  - STL file for 3D printing : under `mecha` directory
- Schematic and PCB design by KiCad7 : under `kicad/extraice` directory

## Firmware

The firmware is written by Rust language.

See [The Rust on ESP Book](https://esp-rs.github.io/book/) for instructions on how to set up the development environment.

The firmware is located under `fsw` directory. This directory is a sub-module, which is actually the micromouse-esp32 repository.
