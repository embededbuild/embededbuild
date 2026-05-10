<div align="center">
  <img src="assets/embededbuild_glitch_logo.png" alt="embededbuild logo" />
</div>

`// you're not supposed to be here. keep going.`

</div>

---

## whoami

i build wireless security hardware. open source. no paywalls.  
ESP32, nRF24, BLE — cheap chips doing things expensive products won't admit they can do.

every device starts the same way:  
*what does this signal know that you don't?*

---

## /devices

| codename | what it is | repo |
|----------|-----------|------|
| **Tank** | ESP32 doing flipper zero things. WiFi scanning, BLE, RF24, probe sniffing, MAC spoofing. built from scratch because buying one felt like giving up. | [![](https://img.shields.io/badge/-Tank-111111?logo=github&logoColor=white&labelColor=9900d1)](https://github.com/embededbuild/Tank) |
| **GlitchRF** | RF dongle. terminal controlled. does more than it should. | [![](https://img.shields.io/badge/-GlitchRF-111111?logo=github&logoColor=white&labelColor=00c0d1)](https://github.com/embededbuild/GlitchRF) |

> *devices get added when they leave the bench and survive field testing*

---

## /tank --capabilities

```
[*] WiFi        — scan all networks or open-only, log to SD
[*] BLE         — enumerate devices, flag AirTags / Tile / SmartTags
[*] RF24        — spectrum scan, packet capture, replay via nRF24L01+
[*] Probe sniff — passive 802.11 probe capture with channel hopping
[*] Spoof       — MAC and IP, saved profiles, persistent across boots
[*] SD logging  — everything gets written. nothing gets forgotten.
```

`hardware` — ESP32 · SSD1306 OLED · nRF24L01+ · MicroSD

---

## /pipeline

```
[DONE]        GlitchRF   — terminal RF dongle
[IN PROGRESS] BLE Ducky  — Bluetooth HID, type without touching a keyboard
[TESTING]     BLE Twin   — BLE evil twin, compiles, not field tested yet
[UNKNOWN]     ???        — more signals. more problems. when it's ready.
```

---

## /method

- ship the schematics. ship the firmware. ship the docs. no exceptions.
- ESP32 and RP2040 — not because it's easy, because it's honest about what it costs
- security tools shouldn't require a $200 purchase to understand what's around you

---

## /contact

```
github    → github.com/embededbuild
instagram → instagram.com/embeddedbuild
```

---

## /exit

didn't buy a Flipper Zero.  
built Tank instead.  
that was just the first commit.

```
> connection closed by remote host.
```

---

<sub>all hardware is for authorized security research and educational use only. you own what you do with it.</sub>
