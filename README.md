# GPS L5 firmware installer

Static site that flashes the `um980_ble_bridge` firmware to Heltec Tracker /
Wireless V3 / V4 / V2 / Elecrow LoRaWAN Gateway boards directly from the
browser via Web Serial.

Open: **<https://elitzurms-art.github.io/gps_l5-installer/>**

Binaries here are **auto-published** by the [gps_l5](https://github.com/elitzurms-art/gps_l5)
CI on every push to `master`. Do not edit firmware files in this repo by
hand — they will be overwritten on the next CI run. To change the firmware,
edit `firmware/heltec/um980_ble_bridge/` in the source repo.
