# Jolly BUS Pirate — Usage

## Your first connection (safe practice)

Start on a cheap practice target you own — a loose EEPROM chip, a dev board, or an old
gadget you don't mind poking.

1. **UART** mode: connect to a board's debug header and read its boot messages.
2. **I²C** mode: run a bus **scan** — it lists the addresses of chips on the bus.
3. **SPI** mode: read a flash chip's ID.

Exact commands depend on firmware version — type `help` at the prompt, or use the GUI (https://github.com/p0lygl07/esp32-bit-pirate-gui).

## Learning path
UART → I²C scans → SPI reads → then try the **7 Seas CTF** badge for a guided challenge.

> Only connect to hardware you own or are authorized to test. See docs/SAFETY.md.

