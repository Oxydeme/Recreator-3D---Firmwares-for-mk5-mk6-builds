# Recreator3D – Custom Marlin 2.1.2.7 Firmwares for MK5 & MK6 Builds

[![Marlin Firmware](https://img.shields.io/badge/Marlin-2.1.2.7-blue.svg)](https://github.com/MarlinFirmware/Marlin)
[![Recreator3D Project](https://img.shields.io/badge/Project-Recreator3D-green.svg)](https://www.recreator3d.com)
[![rPET Filament](https://img.shields.io/badge/Recycling-rPET-green.svg?logo=recycle&logoColor=white)](https://www.recreator3d.com)
**Custom Marlin 2.1.2.7 firmware builds optimized for Recreator3D MK5 and MK6 plastic pultrusion and recycling units.**

Convert plastic bottles (rPET, HDPE, PETG, PLA, PP) into usable 3D printing filament with dedicated motherboard builds, customized screen menus, pultrusion motor controls, and Filaruptor support.

<p align="center">
  <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000630.jpg" width="600" alt="Recreator3D Pultrusion Unit with Custom Firmware Display">
</p>

🌐 Official Website: [www.recreator3D.com](https://www.recreator3d.com)

---

## Key Features

### Core Pultrusion Firmware Features
- **Marlin 2.1.2.7 Base:** Updated with high-stability core logic.
- **Customized UI:** Custom Bootscreen, Status Screen, and Info Screen tailored for plastic recycling (3D printer bed icons removed).
- **Branded Status Screen:** X, Y, Z position indicators replaced with `>www.recreator3D.com`.
- **Integrated Pultrude OPT Program:** Designed in collaboration with @JoshuaTaylor for continuous pultrusion operation until manually stopped.
- **Dedicated Controls:** Dedicated **STOP** and **PAUSE** execution buttons.

### Advanced Plastic Recycling Settings
- **Speed Control:** Adjustable pultrusion motor speed, from ultra-slow feeding up to 1800.
- **Preset Materials:** Quick temperature and speed profiles for **rPET**, **HDPE**, **PLA**, **PETG**, and **PP**.
- **Bi-Directional Spooler:** Selectable spooler rotation direction (Roll) ensuring full compatibility with both MK5 and MK6 configurations.
- **Filaruptor & PID AutoTune:** Supported filaruptor sensors (build-dependent) and onboard PID tuning for stable hotend temperatures.
- **Multilingual Support:** Menu toggleable between English, French, and Spanish.
- **R3D Emergency Menu:** Alternative direct command menu for quick manual overrides.

---

## Firmware Downloads (Pre-compiled Binaries)

> 📦 **Download ready-to-flash binaries from the latest [Releases Page](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/latest).**

Find the compiled firmware matching your specific 3D printer motherboard, MCU chip, and display screen.

> ⚠️ **IMPORTANT:** Always verify your exact MCU version and motherboard revision before flashing to prevent bricking your board.

### Anet Motherboards
| Board & Screen Configuration | Download Link |
|---|---|
| Anet 1.7 + RepRapDiscount Smart Controller | [`firmwareAnet1.7.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareAnet1.7.elf) |

### BigTreeTech (BTT) Boards
| Board & Screen Configuration | Download Link |
|---|---|
| BTT Octopus 1.1 + Ender 3 Pro Screen (Dual Pultruder) | [`firmwareOctopus1.1dual.zip`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareOctopus1.1dual.zip) |
| BTT SKR Mini E3 V1.1 + BTT Mini12864 V2 | [`firmwareSkrMiniE3v1.1.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v1.1.bin) |
| BTT SKR Mini E3 V2.0 + BTT Mini12864 V2.1 | [`firmwareSkrMiniE3v2.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v2.bin) |
| BTT SKR Mini E3 V3.0 + Ender 3 Pro Screen | [`firmwareSkrMiniE3v3.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSkrMiniE3v3.bin) |

### Formbot / Fysetc Cheetah Boards
| Board & Screen Configuration | Download Link |
|---|---|
| Cheetah 1.1b + Ender 3 Pro Screen | [`firmwareCheetah1.1b.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCheetah1.1b.elf) |

### Creality 8-bit Boards (1.1.3 / 1.1.4)
| Board & Screen Configuration | Download Link |
|---|---|
| Creality 1.1.3 + Ender 3 Pro Screen | [`firmwareCreality1.1.3.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality1.1.3.elf) |
| Creality 1.1.4 + Ender 3 Pro Screen | [`firmwareCreality1.1.4.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality1.1.4.elf) |

### Creality 32-bit 4.2.2 (GigaDevice GD MCUs)
| MCU Chip Variant | Firmware File |
|---|---|
| GD32F303 Ret6 Variant A | [`firmwareCreality4.2.2_GD_A.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_A.bin) |
| GD32F303 Ret6 Variant B | [`firmwareCreality4.2.2_GD_B.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_B.bin) |
| GD32F303 Ret6 Variant C | [`firmwareCreality4.2.2_GD_C.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_C.bin) |
| GD32F303 Ret6 Variant E | [`firmwareCreality4.2.2_GD_E.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_E.bin) |
| GD32F303 Ret6 Variant H | [`firmwareCreality4.2.2_GD_H.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_H.bin) |
| GD32F303 Ret6 Variant H8 | [`firmwareCreality4.2.2_GD_H8.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_GD_H8.bin) |

### Creality 32-bit 4.2.2 (STM32 MCUs)
| MCU Chip Variant | Firmware File |
|---|---|
| STM32F103 Ret6 Variant A | [`firmwareCreality4.2.2_STM_A.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_A.bin) |
| STM32F103 Ret6 Variant B | [`firmwareCreality4.2.2_STM_B.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_B.bin) |
| STM32F103 Ret6 Variant C | [`firmwareCreality4.2.2_STM_C.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_C.bin) |
| STM32F103 Ret6 Variant E | [`firmwareCreality4.2.2_STM_E.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_E.bin) |
| STM32F103 Ret6 Variant H | [`firmwareCreality4.2.2_STM_H.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_H.bin) |
| STM32F103 Ret6 Variant H8 | [`firmwareCreality4.2.2_STM_H8.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_H8.bin) |
| STM32F103 Ret6 Variant T8 | [`firmwareCreality4.2.2_STM_T8.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.2_STM_T8.bin) |

### Creality 4.2.7 & 4.3.1 Silent Boards
| Board & Screen Configuration | Download Link |
|---|---|
| Creality 4.2.7 Silent Board + Ender 3 Pro Screen | [`firmwareCreality4.2.7.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.2.7.bin) |
| Creality 4.3.1 Silent Board + Ender 3 Pro Screen | [`firmwareCreality4.3.1.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareCreality4.3.1.bin) |

### Elegoo & MKS Boards
| Board & Screen Configuration | Download Link |
|---|---|
| Elegoo Robin Nano 1.2 + Ender 3 Pro Screen | [`firmwareElegooRobinNano1.2.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareElegooRobinNano1.2.bin) |
| Elegoo Robin Nano 1.3 + Ender 3 Pro Screen | [`firmwareElegooRobinNano1.3.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareElegooRobinNano1.3.bin) |
| MKS Gen L1.0 + Ender 3 Pro Screen | [`firmwareMKSGenL1.elf`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareMKSGenL1.elf) |
| MKS Robin E3 + Ender 3 Pro Screen | [`firmwareMKSRobin_e3.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareMKSRobin_e3.bin) |

### Sovol Boards
| Board & Screen Configuration | Download Link |
|---|---|
| Sovol SV06 Mainboard + CR-10 Screen | [`firmwareSV06.bin`](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/download/Update/firmwareSV06.bin) |

---

## User Interface Screenshots

| Screen View | Description |
|---|---|
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000626.jpg" width="300" alt="Marlin Firmware 2.1.2.7 Version Display"> | **Firmware 2.1.2.7 Build Version** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000625.jpg" width="300" alt="Recreator3D Custom Bootscreen Logo"> | **Custom Bootscreen** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173251.jpg" width="300" alt="Recreator3D Status Screen Display"> | **Status Screen** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000649.jpg" width="300" alt="Recreator3D Machine Info Screen"> | **Info Screen** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173311.jpg" width="300" alt="Pultrusion STOP and PAUSE Control Menu"> | **STOP / PAUSE Controls** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173403.jpg" width="300" alt="Pultrusion Pulling Speed Adjustment Menu"> | **Pultrusion Speed Selection** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173413.jpg" width="300" alt="Plastic Material Selection rPET PLA PETG HDPE"> | **Material Profile Selection** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173320.jpg" width="300" alt="Recreator3D Spooler Rotation Direction Setup"> | **Spooler Direction (MK5/MK6)** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173328.jpg" width="300" alt="Multilingual Menu Interface English French Spanish"> | **Language Selection** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261104_173335.jpg" width="300" alt="R3D Emergency Command Menu Interface"> | **Emergency Command Interface** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000725.jpg" width="300" alt="Filaruptor Filament Sensor Interface"> | **Filaruptor Sensor Menu** |
| <img src="https://raw.githubusercontent.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/assets/IMG_20261105_000808.jpg" width="300" alt="Hotend PID AutoTune Setup Menu"> | **PID AutoTune Calibration** |

---

## Installation Guide

1. **Identify Hardware:** Check your mainboard model and exact MCU chip (e.g., STM32 vs GigaDevice GD32).
2. **Check Display:** Confirm your screen interface type (e.g., Ender 3 Pro LCD, BTT Mini12864, RepRapDiscount).
3. **Download Firmware:** Get the corresponding `.bin` or `.elf` file from the [Releases section](https://github.com/Oxydeme/Recreator-3D---Firmwares-for-mk5-mk6-builds/releases/latest).
4. **Flash Mainboard:**
   - For 32-bit boards (Creality 4.2.2, BTT SKR, Elegoo): Copy the `.bin` file to a formatted FAT32 micro-SD card (8GB or smaller), insert it into the board, and power on.
   - For 8-bit boards (Anet 1.7, Creality 1.1.3): Flash the `.elf` file using AVRDUDE or ProgISP with your ISP programmer.
5. **Initial Test:** Run a test hotend heating and low-speed spooler rotation before executing full pultrusion jobs.

---

## Official Recreator3D Project Links

### Recreator3D MK5
- [Recreator3D MK5 Kit – Ender 3 Conversion Guide](https://www.recreator3d.com/mk5kitender3)
- [MK5 Printable Files – Printables 3D Models](https://www.printables.com/model/179820-recreator-3d-mk5kit-ender3-pultrusion-unit?lang=fr)

### Recreator3D MK6
- [Recreator3D MK6 FunSize Documentation](https://www.recreator3d.com/mk6funsize)
- [MK6 Printable Files – Printables 3D Models](https://www.printables.com/model/352729-the-recreator-3d-mk6-diy-bom-turn-pet1-plastic-bot?lang=fr)

---

## Frequently Asked Questions (FAQ)

<details>
<summary><b>How do I determine if my Creality 4.2.2 board uses an STM32 or GD32 chip?</b></summary>
<br>
Inspect the large square processor chip on your Creality motherboard. If the text begins with <code>STM32F...</code>, flash an <b>STM</b> firmware build. If it starts with <code>GD32F...</code>, flash a <b>GD</b> firmware build.
</details>

<details>
<summary><b>Why is my spooler spinning backwards?</b></summary>
<br>
Go to the firmware menu and select <b>Spooler Rotation Direction</b> to toggle the rotation direction between MK5 and MK6 mounting configurations without rewiring your stepper motor.
</details>

---

## Credits & Acknowledgments

- **[Marlin Firmware](https://github.com/MarlinFirmware/Marlin):** Powerful open-source 3D printer firmware base.
- **@JoshuaTaylor:** Project Creator & Original Developer.
- **[Recreator3D Community](https://www.recreator3d.com/):** For driving open-source plastic recycling innovation.

---

<p align="center">
  <b>Recreator3D – Turning plastic bottle waste into functional 3D printer filament.</b>
</p>
