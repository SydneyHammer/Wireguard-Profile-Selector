# wg-select

**wg-select** is a command-line tool for quickly switching between WireGuard profiles. I created it because I was tired of always having to check which profile is running, then having to disable it with `sudo wg-quick down [profile]` and then enabling the new one with `sudo wg-quick up [new-profile]`

## Requirements

Before using **wg-select**, ensure that you have installed `fzf`. You can install it on Debian-based systems using:

```
sudo apt install fzf
```

## Features

- Presents a list of available WireGuard profiles from `/etc/wireguard`.
- Automatically stops any running WireGuard profile before enabling the selected one.

## Usage

1. Clone this repository.
2. Make sure you have installed `fzf`.
3. Run `wg-select` to start the profile selection process.


``` ```
