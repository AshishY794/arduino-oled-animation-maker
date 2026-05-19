# OLED Display Animation Maker for Arduino

> **Create animations for Arduino** — free online **OLED animation maker** for **SSD1306**, **SH1106**, and **128×64** displays. No install. No account.

[![Open OLED Animation Maker — Free](https://img.shields.io/badge/▶_Open_Tool-oledanimationmaker.com-2563eb?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0iI2ZmZiIgZD0iTTggNXYxNGwxMS03eiIvPjwvc3ZnPg==)](https://oledanimationmaker.com)
[![License: MIT](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<p align="center">
  <a href="https://oledanimationmaker.com">
    <img src="https://oledanimationmaker.com/og-image.png" alt="OLED display animation maker for Arduino — create SSD1306 and SH1106 animations online" width="720">
  </a>
</p>

<p align="center">
  <strong>
    <a href="https://oledanimationmaker.com">oledanimationmaker.com</a>
  </strong>
  — the free <strong>OLED display animation</strong> editor for makers, students, and Arduino projects.
</p>

---

## What is OLED Display Animation Maker?

**OLED Display Animation Maker** is a browser-based **OLED animation maker for Arduino**. It helps you build **OLED display animations** without hand-writing huge `PROGMEM` bitmap arrays.

Use it to:

- **Create animations for Arduino** with 100+ ready-made templates (loaders, weather, icons, text effects)
- **Draw** custom pixel art on a **128×64** (or other) timeline
- **Import GIF or PNG** and convert to monochrome OLED frames
- **Preview** on a virtual screen or **live on real hardware** via WebSerial (Chrome / Edge)
- **Export code** for **Adafruit SSD1306**, **U8g2**, or **MicroPython** in one click

**👉 Start here: [https://oledanimationmaker.com](https://oledanimationmaker.com)**

---

## Who is this for?

| You are building… | This tool helps with… |
|-------------------|------------------------|
| Arduino Uno / Nano / Mega + **0.96" SSD1306** | I²C OLED animation + `.ino` export |
| **ESP32** / **ESP8266** OLED projects | WebSerial live preview, ESP wiring notes |
| **Raspberry Pi Pico** (MicroPython) | `framebuf` Python export |
| **SH1106** 128×64 modules | Offset-aware generated code |
| School / hobby **OLED bitmap** lessons | Visual editor instead of hex arrays |

---

## How to create an OLED animation (3 steps)

1. **Choose an animation** — open [oledanimationmaker.com](https://oledanimationmaker.com), pick a template or import a GIF.
2. **Edit & preview** — use **Animate** mode, set FPS, preview on the virtual OLED (or connect hardware).
3. **Get the code** — download **Arduino** (`.ino`) or **MicroPython** (`.py`) with ready bitmaps and playback loop.

Same workflow as professional **OLED animator** tools — optimized for **Arduino OLED animation** workflows.

---

## Features

| Feature | SEO / search terms |
|--------|---------------------|
| **100+ animation templates** | oled animation maker, oled display animation |
| **650+ Icons8 Lottie icons** | arduino oled icons, ssd1306 ui animation |
| **Pixel editor + timeline** | oled bitmap generator arduino |
| **GIF → OLED converter** | gif to oled arduino, gif to ssd1306 |
| **Image → byte array export** | image to byte array arduino, image2cpp alternative |
| **OLED pixel editor** | oled pixel editor, oled animations |
| **SSD1306 & SH1106** | ssd1306 animation, sh1106 oled animation |
| **128×64, 128×32, 64×48** | 128x64 oled animation, 0.96 oled animation |
| **WebSerial live preview** | esp32 oled animation, live oled preview |
| **Adafruit / U8g2 / framebuf** | adafruit ssd1306 animation, u8g2 animation generator |
| **Free, no install** | free oled animation tool |

---

## Supported hardware & displays

### Boards

- Arduino Uno, Nano, Mega  
- ESP32, ESP8266 (Wemos D1)  
- STM32 (Wire pins in receiver sketch)  
- Raspberry Pi Pico — **MicroPython**

### OLED modules

- **SSD1306** — 128×64, 128×32, 64×48, 96×16  
- **SH1106** — 128×64 (column offset handled in export)  
- I²C addresses **0x3C** and **0x3D**

### Libraries (exported code)

- Adafruit SSD1306 + GFX  
- U8g2  
- MicroPython `framebuf`

---

## Popular searches this tool solves

| People search for… | What you get at oledanimationmaker.com |
|--------------------|----------------------------------------|
| **oled animation maker** | Online editor + instant export |
| **oled animations** | Multi-frame templates + timeline playback |
| **arduino oled animation** | Ready `.ino` / `.py` sketches |
| **arduino oled code generator** | One-click Adafruit / U8g2 / MicroPython |
| **ssd1306 animation** | PROGMEM bitmaps + frame loop |
| **ssd1306 code generator** | Copy-paste Arduino C++ |
| **gif to oled arduino** | Import tab → animated frames |
| **image to byte array arduino** | PNG/GIF → PROGMEM arrays + loop |
| **oled bitmap generator arduino** | Draw or template → byte arrays |
| **oled pixel editor** | Draw, animate, export — no install |
| **esp32 oled animation** | ESP32 board preset + WebSerial |
| **micropython oled animation** | Pico / ESP32 MicroPython export |
| **create animations for arduino** | Templates + timeline, no coding required |

---

## Live OLED preview (WebSerial)

Optional but powerful for debugging:

1. Set **board**, **display**, and **I²C address** in the app header.  
2. Copy the **WebSerial receiver sketch** from the app → upload to your board.  
3. Click **Connect** in Chrome or Edge → select USB serial port.  
4. Your physical **OLED display** mirrors frames in real time.

**ESP8266 tip:** SDA → D2, SCL → D1, 3.3V, GND.

---

## FAQ

### Is OLED Display Animation Maker free?

Yes. The full app at **[oledanimationmaker.com](https://oledanimationmaker.com)** is free — no account, no install.

### Do I need to download anything?

No. It runs in your browser. You only download the **generated Arduino or MicroPython code** when you click **Get the Code**.

### Which OLED displays are supported?

**SSD1306** and **SH1106** are fully supported, including common **128×64** and **128×32** sizes.

### Can I convert a GIF to an Arduino OLED animation?

Yes. Use the **Import** tab to load a GIF or PNG; the tool converts frames to monochrome bitmaps and exports playback code.

### Does it work with ESP32?

Yes. Choose ESP32 in board settings, export code, and use **WebSerial** for live preview on a connected OLED.

### Where is the main application?

This repository points to the live product:

**🌐 [https://oledanimationmaker.com](https://oledanimationmaker.com)**

Source code for the full app: [github.com/AshishY794/oledanimationmaker](https://github.com/AshishY794/oledanimationmaker)

---

## Links

| Resource | URL |
|----------|-----|
| **Live app (use this)** | [https://oledanimationmaker.com](https://oledanimationmaker.com) |
| **Sitemap** | [https://oledanimationmaker.com/sitemap.xml](https://oledanimationmaker.com/sitemap.xml) |
| **Full source repo** | [https://github.com/AshishY794/oledanimationmaker](https://github.com/AshishY794/oledanimationmaker) |

---

## GitHub topics (suggested for this repo)

`arduino` `oled` `ssd1306` `sh1106` `animation` `animation-maker` `embedded` `esp32` `esp8266` `micropython` `gif-converter` `pixel-art` `i2c` `128x64` `adafruit` `u8g2` `webserial` `maker` `iot`

---

## Author

**Ashish** — built for the maker community.

- GitHub: [@AshishY794](https://github.com/AshishY794)  
- Website: **[oledanimationmaker.com](https://oledanimationmaker.com)**

If this README helped you find the tool, **star this repo** and share the link with anyone learning **Arduino OLED animations**.

---

## License

MIT License — see [LICENSE](LICENSE) if included in this repository.

Icons8 animations are loaded from the Icons8 CDN inside the web app. Review [Icons8 licensing](https://icons8.com/license) for commercial products.

---

<p align="center">
  <strong>OLED Display Animation Maker</strong> · Create animations for Arduino · SSD1306 & SH1106 · Free online<br>
  <a href="https://oledanimationmaker.com"><strong>oledanimationmaker.com</strong></a>
</p>
