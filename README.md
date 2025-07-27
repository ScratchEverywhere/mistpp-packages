# Homebrew Packages for Mist++

## Installation

The easiest way to install Mist++ for Homebrew is by just downloading the
packages from the latest release and installing them with `(dkp-)pacman -U`.

### Manual

First you need to clone this repo with:

```sh
git clone https://github.com/gradylink/mistpp-packages
```

Then, enter the folder of the package you want to install (`cd wiiu` for the Wii
U and `cd 3ds` for the 3DS).

Lastly, run:

```sh
(dkp-)makepkg -si
```

to install the package.

## Updating

Just reinstall with the newest version.
