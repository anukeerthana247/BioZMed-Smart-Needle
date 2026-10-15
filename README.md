# BioZMed – Review 2 Firmware Deliverable

This folder contains an ESP32 diagnostic firmware scaffold.

## Implemented in code
- Serial initialization at 115200 baud
- Startup diagnostic messages
- `HELP`, `STATUS`, `START`, and `STOP` serial commands
- Periodic diagnostic heartbeat
- Handling for unknown and overly long commands

## Not implemented or verified
- Bioimpedance measurement or sensor communication
- Vein-entry or far-wall detection
- Alert thresholds
- Physical ESP32 test (board is awaiting arrival)

## Test when the ESP32 arrives
1. Open `BioZMed_ESP32.ino` in Arduino IDE.
2. Select the correct ESP32 board and port.
3. Upload the sketch.
4. Open Serial Monitor at 115200 baud and set line ending to Newline.
5. Try `HELP`, `STATUS`, `STOP`, and `START`.
6. Record the actual output. This is a firmware/serial test, not an impedance test.
