 <p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/imager3dbanner.png" width="100%" alt="Recreator3D Banner">
</p>

# Recreator3D – Custom Firmwares for MK5 / MK6

**Custom Marlin 2.1.2.7 firmware builds for Recreator3D MK5 and MK6 machines.**

Various motherboard + screen combinations, with dedicated features for plastic recycling and pultrusion.

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000630.jpg" width="600" alt="General">
</p>

🌐 Website: [www.recreator3D.com](https://www.recreator3d.com)

---

# Features

### Core firmware
- Based on Marlin 2.1.2.7.
- Custom Bootscreen, Status Screen and Info Screen.
- Bed icon removed.
- Status icons replaced with custom pultrusion icons and animations.
- X, Y and Z indicators replaced with `>www.recreator3D.com`.

### Pultrusion controls
- Integrated Pultrude OPT program (thanks to @JoshuaTaylor).
- Continuous pultrusion operation until manually stopped.
- Dedicated STOP and PAUSE buttons.
- Adjustable pultrusion speed, from very slow operation up to 1800.
- Material selection: rPET, HDPE, PLA, PETG and PP.
- Selectable spooler rotation direction (Roll), making the firmware compatible with MK5 and MK6 configurations.
- Filaruptor support, depending on firmware build.

### User interface
- Three selectable languages directly from the menu:
  - English
  - French
  - Spanish
- Dedicated R3D Emergency Command menu as an alternative command interface.
- Custom interface designed specifically for Recreator3D.

### Maintenance
- Integrated PID AutoTune.

---

# Screenshots

### Firmware 2.1.2.7

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000626.jpg" width="600" alt="Firmware 2.1.2.7">
</p>

### Bootscreen

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000625.jpg" width="600" alt="Bootscreen">
</p>

### Status Screen

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173251.jpg" width="600" alt="Status Screen">
</p>

### Info Screen

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000649.jpg" width="600" alt="Info Screen">
</p>

### STOP / PAUSE

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173311.jpg" width="600" alt="STOP and PAUSE">
</p>

### Pultrusion Speed Selection

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173403.jpg" width="600" alt="Speed">
</p>

### Material Selection

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173413.jpg" width="600" alt="Material">
</p>

### Spooler Rotation Direction

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173320.jpg" width="600" alt="Spooler rotation">
</p>

### Language Selection

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173328.jpg" width="600" alt="Language Selection">
</p>

### R3D Emergency Command

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173335.jpg" width="600" alt="R3D Emergency Command">
</p>

### R3D Firmware Interface

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173341.jpg" width="600" alt="R3D Firmware">
</p>

### Filaruptor

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000725.jpg" width="600" alt="Filaruptor">
</p>

### PID AutoTune

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000808.jpg" width="600" alt="PID AutoTune">
</p>

---

# Recreator3D Projects

### MK5

- [Recreator3D MK5 Kit – Ender 3](https://www.recreator3d.com/mk5kitender3)
- [MK5 Printable Files – Printables](https://www.printables.com/model/179820-recreator-3d-mk5kit-ender3-pultrusion-unit?lang=fr)

### MK6

- [Recreator3D MK6 FunSize](https://www.recreator3d.com/mk6funsize)
- [MK6 Printable Files – Printables](https://www.printables.com/model/352729-the-recreator-3d-mk6-diy-bom-turn-pet1-plastic-bot?lang=fr)

---

# Firmware Downloads

**Marlin 2.1.2.7 – Available builds**

Choose the firmware matching your motherboard, MCU variant and screen configuration.

> ⚠️ **IMPORTANT:** Do not flash a firmware intended for a different MCU variant or motherboard. Verify your hardware before installation.

## Anet

| Configuration | Firmware |
|---|---|
| Anet 1.7 + ReprapSmart Screen | `firmwareAnet1.7.elf` |

## BigTreeTech (BTT)

| Configuration | Firmware |
|---|---|
| Octopus 1.1 + E3Pro Screen | `firmwareOctopus1.1dual.zip` |
| SKR Mini E3 V1 + BTT Mini12864 V2 | `firmwareSkrMiniE3v1.1.bin` |
| SKR Mini E3 V2 + BTT Mini12864 V2.1 | `firmwareSkrMiniE3v2.bin` |
| SKR Mini E3 V3 + E3Pro Screen | `firmwareSkrMiniE3v3.bin` |

**Special build:** Octopus 1.1 version optimized for dual pultruding.

## Cheetah

| Configuration | Firmware |
|---|---|
| Cheetah 1.1b + E3Pro Screen | `firmwareCheetah1.1b.elf` |

## Creality 1.1.3 / 1.1.4

| Configuration | Firmware |
|---|---|
| Creality 1.1.3 + E3Pro Screen | `firmwareCreality1.1.3.elf` |
| Creality 1.1.4 + E3Pro Screen | `firmwareCreality1.1.4.elf` |

## Creality 4.2.2 – GD MCU

| MCU variant | Firmware |
|---|---|
| GD A | `firmwareCreality4.2.2_GD_A.bin` |
| GD B | `firmwareCreality4.2.2_GD_B.bin` |
| GD C | `firmwareCreality4.2.2_GD_C.bin` |
| GD E | `firmwareCreality4.2.2_GD_E.bin` |
| GD H | `firmwareCreality4.2.2_GD_H.bin` |
| GD H8 | `firmwareCreality4.2.2_GD_H8.bin` |

## Creality 4.2.2 – STM32 MCU

| MCU variant | Firmware |
|---|---|
| STM A | `firmwareCreality4.2.2_STM_A.bin` |
| STM B | `firmwareCreality4.2.2_STM_B.bin` |
| STM C | `firmwareCreality4.2.2_STM_C.bin` |
| STM E | `firmwareCreality4.2.2_STM_E.bin` |
| STM H | `firmwareCreality4.2.2_STM_H.bin` |
| STM H8 | `firmwareCreality4.2.2_STM_H8.bin` |
| STM T8 | `firmwareCreality4.2.2_STM_T8.bin` |

## Creality 4.2.7

| Configuration | Firmware |
|---|---|
| Creality 4.2.7 + E3Pro Screen | `firmwareCreality4.2.7.bin` |

## Creality 4.3.1

| Configuration | Firmware |
|---|---|
| Creality 4.3.1 + E3Pro Screen | `firmwareCreality4.3.1.bin` |

## Elegoo

| Configuration | Firmware |
|---|---|
| Robin Nano 1.2 + E3Pro Screen | `firmwareElegooRobinNano1.2.bin` |
| Robin Nano 1.3 + E3Pro Screen | `firmwareElegooRobinNano1.3.bin` |

## MKS

| Configuration | Firmware |
|---|---|
| MKS Gen L1 + E3Pro Screen | `firmwareMKSGenL1.elf` |
| MKS Robin + E3Pro Screen | `firmwareMKSRobin_e3.bin` |

## Other boards

| Configuration | Firmware |
|---|---|
| SV06 + CR10 Screen | `firmwareSV06.bin` |

---

# Installation

1. Identify your motherboard and MCU variant.
2. Verify your screen configuration.
3. Download the matching firmware.
4. Follow the appropriate flashing procedure for your board.
5. Verify the machine operation before starting a pultrusion job.

Always keep a backup of your original firmware and configuration.

---

# Credits

- [Marlin Firmware](https://github.com/MarlinFirmware/Marlin) – Open-source firmware foundation.
- @JoshuaTaylor – Project Creator
- [Recreator3D](https://www.recreator3d.com/) – MK5 and MK6 projects.

---

<p align="center">
  **Recreator3D – Turning plastic waste into something useful.**
</p>
