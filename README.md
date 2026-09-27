# Moonraker - API Web Server for Klipper

> **This repository is a experimental fork of Moonraker.**

This fork is intended to add support for custom Arduino-based power devices and other customizations that may be needed for future projects.

## Why the fork?

Moonraker supports extending its functionality through components. However, this fork is intended to modify the behavior of existing components where needed. Maintaining those changes directly in a fork is cleaner and more practical for my use case than implementing them as separate components.

## Relationship to upstream

I intend to keep this fork as close to upstream Moonraker as practical. However, I may not always sync with upstream promptly.

If you notice that this fork has fallen significantly behind upstream, feel free to open an issue and let me know.

## Original README

Moonraker is a Python 3 based web server that exposes APIs with which
client applications may use to interact with the 3D printing firmware
[Klipper](https://github.com/KevinOConnor/klipper). Communication between
the Klippy host and Moonraker is done over a Unix Domain Socket.  Tornado
is used to provide Moonraker's server functionality.

Documentation for users and developers can be found on
[Read the Docs](https://moonraker.readthedocs.io/en/latest/).

### Clients

Note that Moonraker does not come bundled with a client, you will need to
install one.  The following clients are currently available:

- [Mainsail](https://github.com/mainsail-crew/mainsail) by [Mainsail-Crew](https://github.com/mainsail-crew)
- [Fluidd](https://github.com/fluidd-core/fluidd) by Cadriel
- [KlipperScreen](https://github.com/jordanruthe/KlipperScreen) by jordanruthe
- [mooncord](https://github.com/eliteSchwein/mooncord) by eliteSchwein

### Raspberry Pi Images

Moonraker is available pre-installed with the following Raspberry Pi images:

- [MainsailOS](https://github.com/mainsail-crew/MainsailOS) by [Mainsail-Crew](https://github.com/mainsail-crew)
  - Includes Klipper, Moonraker, and Mainsail
- [FluiddPi](https://github.com/fluidd-core/FluiddPi) by Cadriel
  - Includes Klipper, Moonraker, and Fluidd

### Docker Containers

The following projects deploy Moonraker via Docker:

- [prind](https://github.com/mkuf/prind) by mkuf
  - A suite of containers which allow you to run Klipper in
    Docker.  Includes support for OctoPrint and Moonraker.

### Changes

Please refer to the [changelog](https://moonraker.readthedocs.io/en/latest/changelog)
for a list of notable changes to Moonraker.
