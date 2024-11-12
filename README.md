# *bluetoothctl* Wrapper

Python Qt wrapper for the linux **bluetoothctl** program.

It provides methods to perform 
  - pairing / removing
  - connecting / disconnecting 
  - scanning
  - trusting / distrusting
  - obtaining device information
  - finding a device by name or mac

Many of these methods are not available in other bluetooth libraries.

## Install
Download the library and ```pip3 install -e .``` or omit the -e switch to install into python's site packages.

## Testing
The main file ```Qbluetoothctl_helper.py``` can be run as a standalone and will conduct a couple of test.
Users can examine the main section and incorporate the functions that fit their needs.

## Dependencies
- PyQt 5
- PyQt 6 untested

Urs Utzinger, 2024