# Original Prusa i3 MK2 Firmware

Note: pins.h has been modified in an attempt to bypass the heating circuit which seems to have failed

## General instructions

Pre-compiled hex output on PRUSA RESEARCH site: http://prusa3d.com/downloads/firmware/

Just download and flash it to the electronics


## Build instructions

### Step 1

Install arduino

### Step 2

Remove Liquid Crystal library from your arduino or rename it

### Step 3

Install the arduino addon located in the root of this repo. Don't forget to install correct version!

### Step 4

Add 'https://raw.githubusercontent.com/ultimachine/ArduinoAddons/master/package_ultimachine_index.json' to the Boards Manager and select it

### Step 5

Copy the configuration file matching your printer from variants folder to the the Firmware folder

### Step 6

Rename it to "Configuration_prusa.h"

### Step 7

Compile the firmware

### Step 8

Upload the firmware to board USING ARDUINO (don't use Prusa's ghetto firmware uploader thing)





