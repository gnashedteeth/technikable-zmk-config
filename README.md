# Context
This is the firmware and keymap for my Technikable Ortholinear keyboard. This is a **44 key QWERTY** layout utilizing a split space bar, mod-tap, and combo features from the ZMK firmware.

## Usage
### Keymap
The keymap is modified in the `boards/arm/technikable/technikable.keymap` file. **GitHub Actions** automatically validate and complile the firmware upon successful commit.

### Bluetooth Tx Power
Signal Transmit strength (Tx PWR) has been modified to suit my current needs. You can find this setting in the `/boards/arm/technikable/kconfig` file.
