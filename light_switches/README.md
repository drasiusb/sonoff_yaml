# sonoff_yaml

#### Test target
[Sonoff M5 SwitchMan 3-Gang](https://devices.esphome.io/devices/Sonoff-M5)

#### Connections
Flash once over USB-TTL (3.3V!) with the switch disconnected from mains:
`3V3-3V3`, `GND-GND`, `TX-RX`, `RX-TX`. Hold the middle button (GPIO00) while powering up.
After that, updates go over the air from Home Assistant.

#### Notes
- Matter version (part number ending in `W`, e.g. `M5-3C-86W`) is locked and cannot be flashed
- USB-TTL may have enough power to flash but not to boot; it boots normally on mains
- Red LEDs are wired to the relays, `Background Brightness` sets their glow when OFF
