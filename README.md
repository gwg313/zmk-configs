# ZMK Personal Configurations

## Build Status and Results

[![Woodpecker CI](https://ci.gwg313.xyz/api/badges/gwg313/zmk-configs/status.svg)](https://ci.gwg313.xyz/gwg313/zmk-configs)
[![Firmware Builds](https://img.shields.io/badge/downloads-firmware-blue)](https://s3-console.gwg313.xyz/browser/zmk-builds)

## Introduction

These are the configurations for my custom keyboard layouts.

## Getting Started

## Configuring Your Keyboard

### Keymap

Adjust the relevant keymap configuration in `config/*.keymap` to define the
function of each key on your keyboard.

You can find my daily keymap [here](config/base_lower.keymap)

## Automated Build and Flash

The firmware is automatically built using GitHub Actions. Once built, it is
uploaded as an artifact. No manual building is required.

To flash them connect a compatable keyboard and enter bootloader mode, then drag
and drop the relevant uf2 files.

## Support

For more information you can view the ZMK docs
[here](https://zmk.dev/docs/development/documentation)

If you have any questions or need assistance, feel free to reach out.

Happy typing!
