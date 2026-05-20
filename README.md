# SMA Interface PCB

KiCad PCB design for a reward-well controller for behavioral neuroscience experiments.

## Function

Built around an **RP2040-Zero** microcontroller. Takes 6 SMA coaxial sensor inputs from the spikegadgets ECU, through a schmitt-trigger buffer, and drives 4 TMC2209 stepper motors for reward dispensing. 8× AO3400A MOSFETs switch light and sounds. Two stacked USB-A ports allow to connect with the reward wells.

## Requirements

- [KiCad](https://www.kicad.org/) 10.0+

Clone with `--recurse-submodules` to pull the [NeuroACT-KiCad-libraries](https://github.com/NeuroACT-NCBS/NeuroACT-KiCad-libraries) automatically:

```bash
git clone --recurse-submodules https://github.com/NeuroACT-NCBS/SMA-interface-pcb.git
```

## KiCad Plugins

- **Fabrication Toolkit** — for generating production Gerber files
- **Round Tracks** — configured via `.round-tracks-config`

## License

CERN Open Hardware Licence Version 2 — see [LICENSE](LICENSE)
