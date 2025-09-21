![Release](https://img.shields.io/github/v/release/lickayd/hirschmann_switches)
![Downloads (latest)](https://img.shields.io/github/downloads/lickayd/hirschmann_switches/latest/total)
![Downloads](https://img.shields.io/github/downloads/lickayd/hirschmann_switches/total)
![License](https://img.shields.io/github/license/lickayd/hirschmann_switches)

# Hirschmann Switches Integration for Home Assistant

_DISCLAIMER: This project is a private open source project and doesn't have any connection with Hirschmann Automation and Control GmbH._

## Features

This integration is a hobby project to include some of Hirschmann's switching products to Home Assistant.

After configuring this integration, the following information is available:

 - Sensor entities for every physical port showing the current link status and, if supported, the PoE status and delivered power value.
 - Switch entities for all physical ports to change the administative status and, if supported, enable PoE feature on the port.
 - Additional sensor entities for diagnostics like system uptime and device temperature. These entities are disabled by default and need to be enabled manually if required.

The following devices are currently supported:

Type | Product code
-- | --
MACH104 | MACH104-20TX-F-4PoE

## Install

### Installation via HACS

Have [HACS](https://hacs.xyz/) installed, this will allow you to update easily.

* Adding this integration to HACS can be done using this button:

    [![image](https://my.home-assistant.io/badges/hacs_repository.svg)](https://my.home-assistant.io/redirect/hacs_repository/?owner=lickayd&repository=hirschmann_switches&category=integration)

    > [!NOTE]
    > If the button above doesn't work, add `https://github.com/lickayd/hirschmann_switches` as a custom repository of type Integration in HACS.

* Click Install on the `Hirschmann Switches` integration.
* Restart the Home Assistant.

### Configuration

Adding the integration to your Home Assistant instance can be done via the UI using this button:

[![image](https://my.home-assistant.io/badges/config_flow_start.svg)](https://my.home-assistant.io/redirect/config_flow_start?domain=hirschmann_switches)

<details><summary>Manual Configuration</summary>

If the button above doesn't work, you can also perform the following steps manually:

* Navigate to your Home Assistant instance.
* In the sidebar, click Settings.
* From the Setup menu, select: Devices & Services.
* In the lower right corner, click the Add integration button.
* In the list, search and select `Hirschmann Switches`.
* Follow the on-screen instructions to complete the setup.
</details>

## Help and Contribution

Feel free to open an issue if you find one and I will do my best to help you. If you want to contribute, your help is appreciated! If you want to add a new feature, add a pull request first so we can chat about the details.
