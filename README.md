# rofi-home-assistant
Control Home Assistant through a menu provided by `rofi`.

## Note: This is a personal fork
This is a fork of [`flxai's rofi-home-assistant`](https://github.com/flxai/rofi-home-assistant) repository. This fork contains a link to a personal Rofi theme of mine, which isn't included in the repository.

I'd make this a private repository, but GitHub doesn't allow making fork private.

## Requirements
* [`rofi`](https://github.com/davatorium/rofi)
* [`hass-cli`](https://github.com/home-assistant-ecosystem/home-assistant-cli)
* [`jq`](https://stedolan.github.io/jq/)

## Usage
Run `bin/rofi-hass-toggle` to get a popup to select which state to toggle.
The selected state will be toggled on selection.

