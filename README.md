# SMA Interface PCB

KiCad PCB design for an SMA-to-USB-A interface board, connecting SMA reward well outputs to a host system.

## Overview

This board translates SMA coaxial signals (e.g., IR beam-break outputs from reward wells) into USB-A connections. It uses optocouplers (EL817) for signal isolation and MOSFETs (AO3400A) for switching, with USB-C power distribution.

## Requirements

- [KiCad](https://www.kicad.org/) 9.0+

Clone with `--recurse-submodules` to pull the [NeuroACT-KiCad-libraries](https://github.com/NeuroACT-NCBS/NeuroACT-KiCad-libraries) automatically:

```bash
git clone --recurse-submodules https://github.com/NeuroACT-NCBS/SMA-interface-pcb.git
```

## KiCad Plugins

- **Fabrication Toolkit** — for generating production Gerber files
- **Round Tracks** — configured via `.round-tracks-config`

## License

GPL-2.0
