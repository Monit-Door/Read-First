# Read-First
This repo will help you decide which path to go down. Read this first to know where/how to start.

# Welcome to the Monit-Door start guide!

This will act as a starting guide for users who wish to take part in building their own DIY security system.

Creating this project will involve various physical tools, and software tools.

You will need to consider various things while proceeding through, such as *which* hardware and software you will be using.

The Monit-Door system versions are split into three tiers: **Gila**, **Tegu**, **Komodo**.

# Gila System
The *Gila System* uses **Raspberry Pi Pico W** microcontrollers as our monitoring devices.
RPi Pico W devices do not come with a camera, users will need to purchase this separately (specific model used is specified later in the guide).
This system is aimed for users who want:
- Low cost security system (2nd lowest)
- Monochrome camera footage
- Additional devices attached to their Pico W like: door/window sensors, alarms, motion sensors, etc.
- Tons of online resources and content to help tinker and modify your system
- Great electronics/IoT learning device (brand new learners)
- Camera footage is currently viewable through Processing (migrating to motionEye HTTP/HTTPS interface)
- Remote access to Pico W camera footage (guide coming soon...but you can always create your own option!)

# Tegu System
The *Tegu System* uses **Espressif ESP32-WROVER** microcontrollers as our monitoring devices.
ESP32-WROVER devices come with an onboard camera attached to the microcontroller, no separate purchase is necessary.
This system is aimed for users who want:
- Lowest cost security system (lowest costs that Monit-Door has at the moment)
- Color | B/W camera footage
- Very easy setup and configuration options
- Great electronics/IoT learning device (more advanced learners)
- Camera footage is viewable through motionEye HTTP interface (currently migrating to HTTPS)
- Remote access to camera footage via VPN service (WireGuard | Tailscale | your own VPN service, user will decide this in upcoming steps)
- Configurable with NAS storage (easy to implement through motionEye interface is you have existing storage options, otherwise a guide will be coming soon...you can alwayscreate your own option!)

# Komodo System
The *Komodo System* uses **Raspberry Pi 3/4** single board computers as our monitoring devices
Raspberry Pi SBCs generally do not come with onboard cameras. Cameras and Pi devices must be purchased separately.
This system is aimed for users who want:
- Low cost security system (3rd lowest)
- The absolute best performance out of all three tiers
- Color | B/W camera footage
- Best camera quality and streaming quality
- Mostly plug-and-play which means there is barely any hands on hastle, but also not a lot of room to learn!
- Configurable with NAS storage (easy to implement through motionEye interface is you have existing storage options, otherwise a guide will be coming soon...you can alwayscreate your own option!)

The TLDR for the above is basiclly: do you want a system based on intermediary device(s) such as Pico W(s), ESP32-WROVER(s), or Raspberry Pi(s)?

When you have chosen one of the tiers above (or if you want to learn more about what each tier requires/provides), please visit that tier's repository:
https://github.com/Monit-Door/Gila-System-PicoW
https://github.com/Monit-Door/Tegu-System-ESP32WROVER
https://github.com/Monit-Door/Komodo-System-RPi

For more in depth looks into what is required for each tier, and what each tier offers, please refer to the wiki found on each tiers repository.
