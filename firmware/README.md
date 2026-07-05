# Firmware

This repo now includes a QMK firmware target for the Mochaboard under `firmware/qmk/mochaboard`.

Build flow:

```sh
cp -r firmware/qmk/mochaboard /path/to/qmk_firmware/keyboards/
cd /path/to/qmk_firmware
qmk compile -kb mochaboard -km default
```

Flash flow:

1. Hold `BOOTSEL` on the Raspberry Pi Pico while plugging it in.
2. Copy the generated `.uf2` file onto the mounted `RPI-RP2` drive.

Hardware summary:

- MCU: Raspberry Pi Pico / RP2040
- Matrix: 5 rows x 14 columns
- Diode direction: `COL2ROW`
