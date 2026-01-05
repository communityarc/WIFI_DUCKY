```txt
██╗    ██╗██╗███████╗██╗    ██████╗ ██╗   ██╗ ██████╗██╗  ██╗
██║    ██║██║██╔════╝██║    ██╔══██╗██║   ██║██╔════╝██║ ██╔╝
██║ █╗ ██║██║█████╗  ██║    ██║  ██║██║   ██║██║     █████╔╝ 
██║███╗██║██║██╔══╝  ██║    ██║  ██║██║   ██║██║     ██╔═██╗ 
╚███╔███╔╝██║██║     ██║    ██████╔╝╚██████╔╝╚██████╗██║  ██╗
 ╚══╝╚══╝ ╚═╝╚═╝     ╚═╝    ╚═════╝  ╚═════╝  ╚═════╝╚═╝  ╚═╝
```

## WiFi Duck (ATmega + ESP)

A WiFi-enabled keystroke injection platform combining an ATmega-based USB HID controller with an ESP WiFi module to execute keyboard payloads wirelessly via a web interface.

## Features
- USB HID keyboard emulation
- WiFi-based payload delivery
- Web interface for script management
- Dual-microcontroller architecture
- Fast and reliable payload execution

## Architecture
- ATmega: USB HID and keystroke execution
- ESP: WiFi access point and web control

## Firmware Files
- atmega_duck.ino
- esp_duck.ino

## Intended Use
Authorized security research, USB HID testing, and educational demonstrations.

## License
MIT License
