# Samsung SSD firmware updater for Linux

## Purpose
There were already some utilities in the AUR for updating Samsung SSD firmware on linux but it was a bit outdated so here we are.
Some code has been taken from [this blogpost](https://blog.quindorian.org/2021/05/firmware-update-samsung-ssd-in-linux.html/).

## Usage
You must launch the script as root.
I tried to make it simple: you provide an Samsung Firmware ISO file as an argument and it'll execute the payload to update your firmware:
```bash
# example
samsung-ssd-fwupdate Samsung_SSD_980_PRO_5B2QGXA7.iso
```

As a bonus (and mostly for my convenience) you can print a list of the [firmware ISOs listed on Samsung website](https://semiconductor.samsung.com/consumer-storage/support/tools/#firmware) with the `-l` or `--list` flag, or download them interactively with the `-d` or `--download` flag

## License
MIT
