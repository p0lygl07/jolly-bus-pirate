# Jolly BUS Pirate — Setup

## First-time setup

### 1. Pick the right USB-C port
The board has **two** USB-C ports. To talk to it, use the **UART/COM** port (the serial
bridge), **not** the native-USB port. Connect it to your computer.

### 2. Open a serial console
Open any serial terminal (PuTTY, `screen`, Arduino Serial Monitor, or our GUI) at:
- **Baud:** `115200`

You should get the Bit Pirate command prompt.

### 3. Or use the GUI
Download **esp32-bit-pirate-gui** (https://github.com/p0lygl07/esp32-bit-pirate-gui) — preset buttons for every mode plus a serial console.

### 4. Wire to a target
Connect the probe leads to pins on a board **you own or are authorized to test**:
- **UART:** TX ↔ RX, RX ↔ TX, GND ↔ GND
- **I²C:** SDA ↔ SDA, SCL ↔ SCL, GND ↔ GND
- **SPI:** MISO/MOSI/SCK/CS as labelled, GND ↔ GND

Always share a common ground and check voltage levels (3.3 V logic) first.

### 5. Re-flashing firmware (only if needed)
Follow the upstream **ESP32 Bit Pirate** guide (https://github.com/geo-tp/ESP32-Bus-Pirate).


---

Stuck? See [TROUBLESHOOTING.md](TROUBLESHOOTING.md). Use responsibly — [SAFETY.md](SAFETY.md).
