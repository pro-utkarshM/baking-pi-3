## Enabling the 'OK' or 'ACT' LED on the Raspberry Pi 3 (Lesson OK01)

In the past, the Raspberry Pi's LEDs were directly connected to GPIO pins, allowing users to control them by manipulating specific pins. However, due to space limitations associated with Bluetooth and WiFi components, the LEDs were relocated from the main GPIO to a virtual GPIO.

This virtual GPIO is managed by the VideoCore GPU.

For more detailed information and resources, you can refer to the following links:

- [Raspberry Pi Bare Metal Part 1](https://adamransom.github.io/posts/raspberry-pi-bare-metal-part-1.html)
- [Raspberry Pi Firmware Wiki - Mailboxes](https://github.com/raspberrypi/firmware/wiki/Mailboxes)
- [Raspberry Pi Firmware Wiki - Accessing Mailboxes](https://github.com/raspberrypi/firmware/wiki/Accessing-mailboxes)
