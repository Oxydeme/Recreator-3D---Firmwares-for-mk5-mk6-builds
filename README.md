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

> 📦 **Download pre-compiled binaries directly from the latest [Releases Page](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/latest).**

**Marlin 2.1.2.7 – Available builds**

Choose the firmware matching your motherboard, MCU variant and screen configuration.

> ⚠️ **IMPORTANT:** Do not flash a firmware intended for a different MCU variant or motherboard. Verify your hardware before installation.

## Anet

| Configuration | Firmware |
|---|---|
| Anet 1.7 + ReprapSmart Screen | [`firmwareAnet1.7.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareAnet1.7.elf) |

## BigTreeTech (BTT)

| Configuration | Firmware |
|---|---|
| Octopus 1.1 + E3Pro Screen | [`firmwareOctopus1.1dual.zip`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareOctopus1.1dual.zip) |
| SKR Mini E3 V1 + BTT Mini12864 V2 | [`firmwareSkrMiniE3v1.1.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v1.1.bin) |
| SKR Mini E3 V2 + BTT Mini12864 V2.1 | [`firmwareSkrMiniE3v2.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v2.bin) |
| SKR Mini E3 V3 + E3Pro Screen | [`firmwareSkrMiniE3v3.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v3.bin) |

**Special build:** Octopus 1.1 version optimized for dual pultruding.

## Cheetah

| Configuration | Firmware |
|---|---|
| Cheetah 1.1b + E3Pro Screen | [`firmwareCheetah1.1b.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCheetah1.1b.elf) |

## Creality 1.1.3 / 1.1.4

| Configuration | Firmware |
|---|---|
| Creality 1.1.3 + E3Pro Screen | [`firmwareCreality1.1.3.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality1.1.3.elf) |
| Creality 1.1.4 + E3Pro Screen | [`firmwareCreality1.1.4.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality1.1.4.elf) |

## Creality
