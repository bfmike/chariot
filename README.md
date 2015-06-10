
Arduino Framework for ESP8266 projects
======================================

This project brings a simple configuration and admin interface to ESP8266 Arduino projects.  The project is a port of an old personal project that gave a simple command line shell to Arduino.

### Features: ###
- On initial boot, starts Wifi access point mode to allow initial configuration
- On boot, initial configuration initial access point mode is disabled after a predetermined time (or completely)
- On boot, if GPIO is held low then re-enable configuration access point mode
- On boot, if GPIO is held low for long time then reset stored configuration and revert to factory
- After boot, provide web interface for system configuration options - including which access points to join
- After boot, provide serial interface for configuration (with authentication)
- After boot, provide telnet interface for configuration (with authentication)
- Maybe, if I can find a really small library, offer SSH configuration
- After boot, provide an API for (your) application configuration options
