# OWON PSU Web Controller

A modern web interface for controlling and monitoring OWON (and compatible) laboratory power supplies via the Web Serial API (e.g. Chrome/Edge).

Available for testing: https://reptil1990.github.io/OwonWebControll/

## Features

- Connect to OWON power supplies via Web Serial API (USB)
- Set target values and limits
- Switch output on/off
- Emergency stop function
- Logbook for all commands and responses
- Responsive, modern UI (usable on mobile devices)

## Requirements

- OWON power supply (e.g. SPM, SPE, P4 series) or compatible device
- Recent Chromium-based browser (Chrome, Edge, Opera, ...)
- Enabled Web Serial API (default in Chrome/Edge)

## Usage

1. **Clone or extract the project**
2. Open `index.html` in your browser
3. Click on "Connect to OWON PSU" and select your power supply
4. Use the settings and measurements as desired

## Notes

- The Web Serial API does **not** work in Firefox or Safari.
- If you experience timeouts: check the USB cable, restart the power supply, reload the browser.
- The power supply firmware must be SCPI compatible.

## Safety

- The emergency stop function immediately switches off the output.
- No data is transmitted to the internet – everything runs locally in your browser.

## License

MIT License with Non-Commercial Clause

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software to use, copy, modify, or distribute the Software for 
**non-commercial purposes only**, subject to the following conditions:

---

**Developed for educational/private use. No guarantee of function or device protection!**

---

Developed with love by reptil1990
