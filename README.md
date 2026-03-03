[![Version: 1.0 Release](https://img.shields.io/badge/Version-1.0%20Release-green.svg)](https://github.com/0x007e/cmd) ![Build](https://github.com/0x007e/cmd/actions/workflows/release.yml/badge.svg) [![License CC By-NC-SA](https://img.shields.io/badge/Hardware-CC--BY--NC--SA--4.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/legalcode)

# `CMD` - Color Matrix Display

The `CMD` is a board with a matrix of [APA102](#additional-information) or any other `SPI` controllable `RGB-LED`. The board itself can be driven with a voltage from `3V3-5V` and controlled over the [APA102 driver library](https://github.com/0x007E/drivers-led-apa102).

| Experience  | Level                                                                               |
|:------------|:-----------------------------------------------------------------------------------:|
| Soldering   | ![?%](https://progress-bar.xyz/40?progress_color=0000ff&suffix=%20Medium&width=120) |

# Downloads

| Type      | File                                                                                                                                                 | Description     |
|:---------:|:----------------------------------------------------------------------------------------------------------------------------------------------------:|:----------------|
| Schematic | [pdf](https://github.com/0x007E/cmd/releases/latest/download/schematic.pdf) / [cadlab](https://cadlab.io/project/30127/main/files)                   | Schematic files |
| Board     | [pdf](https://github.com/0x007E/cmd/releases/latest/download/pcb.pdf) / [cadlab](https://cadlab.io/project/30127/main/files)                         | Board file      |
| Drill     | [pdf](https://github.com/0x007E/cmd/releases/latest/download/drill.pdf)                                                                              | Drill file      |
| PCB       | [zip](https://github.com/0x007E/cmd/releases/latest/download/kicad.zip) / [tar](https://github.com/0x007E/cmd/releases/latest/download/kicad.tar.gz) | KiCAD/Gerber/BoM/Drill files |

# Hardware

The pcb is created with `KiCAD`. All files are built with `github actions` so that they are ready for a production environment.

## PCB

The circuit board is populated on both sides (Top, Bottom). The best way for soldering the `SMD` components is within a vapor phase soldering system and for the `THT` components with a standard soldering system. After placing and soldering the top parts, the board has to be cut off in the middle (white edge).

### Top Layer

![Top Layer](https://github.com/0x007E/cmd/releases/latest/download/top.kicad.png)

### Bottom Layer

![Bottom Layer](https://github.com/0x007E/cmd/releases/latest/download/bottom.kicad.png)

# Additional Information

| Type       | Link                                                                                                      | Description                                        |
|:----------:|:---------------------------------------------------------------------------------------------------------:|:---------------------------------------------------|
| APA102     | [pdf](https://cdn.sparkfun.com/datasheets/Components/LED/APA102C.pdf)                                     | RGB Full Color LED                                 |
| T3A33BRG   | [pdf](https://mm.digikey.com/Volume0/opasdata/d220001/medias/docus/6794/3147_T3A33BRG-H9C0002X1U1930.pdf) | Harvatek Surface Mount PLCC IC+RGB LEDs Data Sheet |

---

R. GAECHTER
