<div align="center">
  <img src="https://raw.githubusercontent.com/embededbuild/embededbuild/main/assets/embededbuild.png" alt="embededbuild logo" width="900"/>
</div>

`// you're not supposed to be here. keep going.`

</div>

---

## whoami

i build wireless security hardware. open source. no paywalls.  
ESP32, Raspberry pico's, and many more — cheap chips doing things expensive products won't admit they can do.

every device starts the same way:  
*what can i make this embeded device do that it shouldn't?*

---

## /devices

| codename | what it is | repo |
|----------|-----------|------|
| **Tank** | ⚡ Fully functional embedded systems prototype. ESP32 doing flipper zero things. WiFi scanning, BLE, RF24, probe sniffing, MAC spoofing. built from scratch because buying one felt like giving up. | [![](https://img.shields.io/badge/-Tank-111111?logo=github&logoColor=white&labelColor=9900d1)](https://github.com/embededbuild/Tank) |
| **GlitchRF** | RF dongle. terminal controlled. does more than it should. | [![](https://img.shields.io/badge/-GlitchRF-111111?logo=github&logoColor=white&labelColor=3d6600)](https://github.com/embededbuild/GlitchRF) |
| **corn_sniff** | a esp32 tool that sits and monitor the nework for devices IP/MAC/hostname. | [![](https://img.shields.io/badge/-corn_sniff-111111?logo=github&logoColor=white&labelColor=220b4e)](https://github.com/embededbuild/corn_sniff)
| **BLE-Twin** | a BLE version of a evil twin | [![](https://img.shields.io/badge/-BLE--TWIN-111111?logo=github&logoColor=white&labelColor=309975)](https://github.com/embededbuild/BLE-TWIN)
| **Mona-Lisa** | a esp32 device that can do WiFi/BLE base attacks and also have the ability to READ/WRITE to card/tags with the RFID capabilities | [![](https://img.shields.io/badge/-Mona--Lisa-111111?logo=github&logoColor=black&labelColor=ed8a0a)](https://github.com/embededbuild/Mona-Lisa)
> *devices get added when they leave the bench and survive field testing*

---

## /pipeline

```
[DONE]        GlitchRF   — terminal RF dongle
[In Planning] BLE Ducky  — Bluetooth HID, type without touching a keyboard
[TESTING]     BLE Twin   — BLE evil twin, compiles, not field tested yet
[DONE]        Tank       — A device use for security audits
[IN Progress] corn_sniff — Corn_sniff is a network esp32 tool
[IN Planning] Mona-Lisa  — Pocket WiFi/BLE tool with RFID capabilities 
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
