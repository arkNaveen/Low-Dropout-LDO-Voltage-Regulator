# Low-Dropout (LDO) Voltage Regulator

Design and simulation of a 1.2V Low-Dropout (LDO) voltage regulator using 130nm CMOS technology in Cadence Virtuoso.

## Features

- Two-stage OTA driving a PMOS pass transistor.
- Miller compensation for loop stability.
- 1pF load capacitor.
- Load regulation: 23mV (1$\mu$A--1mA).
- Line regulation: 12mV (1.5V--2V).
- Phase margin: 43.8°--90.9° across the load range.
- PSRR: 34dB at DC, reducing to 1.7dB at 8.4MHz.
- Load-step settling time: 302ns (1$\mu$A → 100$\mu$A).
- Line-step settling time: 280ns (1.5V → 2V).

## Repository Contents

This repository contains the **Cadence Virtuoso simulation/design files** for the LDO, including the schematics and simulation setup used for characterization.

## Technology

- CMOS Technology: 130nm
- Tool: Cadence Virtuoso
- Output Voltage: 1.2V
- Load Capacitance: 1pF
