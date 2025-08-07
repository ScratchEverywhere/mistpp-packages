# Homebrew Packages for Mist++

## Installation

> [!NOTE]
> Mist++ currently relies on modified curl packages for the Wii U and 3DS.
>
> You can find these packages at
> https://github.com/gradylink/wut-packages/tree/feat/curl (Wii U) and
> https://github.com/gradylink/dkp-pacman-packages/tree/feat/3ds-curl (3DS).
>
> To install the Wii U package run `cd curl && (dkp-)makepkg -si`, and for the
> 3DS package it's `cd 3ds/curl && (dkp-)makepkg -si`.

The easiest way to install Mist++ for Homebrew is by just downloading the
packages from the latest release and installing them with `(dkp-)pacman -U`.

### Manual

First you need to clone this repo with:

```sh
git clone https://github.com/gradylink/mistpp-packages
```

Then, enter the folder of the package you want to install (`cd wiiu` for the Wii
U, `cd 3ds` for the 3DS, and `cd wii` for the Wii).

Lastly, run:

```sh
(dkp-)makepkg -si
```

to install the package.

## Updating

Just reinstall with the newest version.
