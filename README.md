# Ryzentosh B450

OC files for BigSur

### Hardware

MSI Tomahawk B450

Ryzen 5 3600

Powercolor RX5700 Red Devil

### Required Steps

* Fix USB Mapping
* I needed to disable Serial Port in bios to stop getting black screen

### Quirks

* I included a patched DSDT to disable PTXH USB Hub in OSX because it caused instawake for me. The reason is that I have an RGB led in my CPU Cooler plugged into it.
