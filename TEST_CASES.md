# Firmware test cases

Prepared for execution when an ESP32 board is available. These tests have not been run yet.

| ID | Input/action | Expected result | Status |
|---|---|---|---|
| TC-01 | Power on/reset | Startup banner appears | Not run |
| TC-02 | Send `STATUS` | Diagnostic status prints | Not run |
| TC-03 | Send `STOP` | Periodic heartbeat stops | Not run |
| TC-04 | Send `START` | Periodic heartbeat resumes | Not run |
| TC-05 | Send `HELP` | Command list appears | Not run |
| TC-06 | Send unknown command | Helpful error message appears | Not run |
| TC-07 | Send an overlong command | Input is cleared and error reported | Not run |

These checks validate serial/firmware behaviour only, not impedance sensing or needle-position detection.
