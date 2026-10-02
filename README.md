# ESP32-S3 Super Mini — KiCad Footprint

KiCad footprint for the **ESP32-S3 Super Mini** module THT version (`MODULE_ESP32-S3-SuperMiniTHT`).
This footprint ONLY includes the main THT holes for the GPIO pins on the two sides, for anyone that might prefer that

![Footprint preview](1.png)

3D view:

![3D view](2.png)

## Pinout

| Left side | Right side |
|---|---|
| TX, RX, 1–7 | 5V, GND, 3V3, 13, 12, 11, 10, 9, 8 |

- **5V** — 5 V input
- **3V3** — 3.3 V output
- **GND** — ground

## Installation

1. Copy the `.kicad_mod` file into your local KiCad footprint library folder.
2. In KiCad, open **Preferences → Manage Footprint Libraries** and add the folder as a new library, or place the file inside an existing project-specific library.
3. Search for `ESP32-S3-SuperMiniTHT` in the footprint chooser.

## Usage

Assign this footprint to your ESP32-S3 Super Mini symbol in the schematic editor, then update the PCB from schematic as usual.

## License

MIT
