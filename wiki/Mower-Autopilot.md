# Mower autopilot

[rmx-mower-autopilot](https://github.com/rmx-lt/rmx-mower-autopilot) is the firmware of the mower's autopilot board (Guition JC-ESP32P4-M3-DEV, ESP32-P4): sensors, motion and blade control, and safety. It stops the mower by itself when the link to the gateway board or the server's command acknowledgements are lost, and never relies on the server to stop the blades.

**Status:** no code yet.

## Related pages

- [Mower-Hardware](Mower-Hardware): the two boards and the UART link between them
- [Mower-Gateway](Mower-Gateway): the board that carries the LTE link to the server
- [Mower-Gateway-Probe](Mower-Gateway-Probe): the diagnostic firmware for that link

## Work

The [Blade of Grass project board](https://github.com/orgs/rmx-lt/projects/1).
