# Jolly BUS Pirate — Troubleshooting

### No serial prompt
Wrong USB-C port. Use the **UART/COM** port, not native USB. Confirm 115200 baud and the right COM port.

### Garbage characters
Baud mismatch — set the terminal to 115200.

### Can't see a target chip on I²C
Check wiring (SDA/SCL not swapped), share a common GND, power the target. Some buses need pull-ups.

### Device not detected
Try the other USB-C cable/port and a data cable. Install the USB-serial driver if needed (CP210x/CH34x).

---

Still stuck? Open an issue here, or message us via https://p01ylabs.com.
