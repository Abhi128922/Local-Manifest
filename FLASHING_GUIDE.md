# ⚡ Axion Os — Installation Guide for OnePlus 12R (Aston)

> Welcome to Axion Os for OnePlus 12R.

## ⚠️ Important Notes

- Make sure your device is OnePlus 12R (Aston).
- Backup all important data before flashing.
- Ensure your battery is sufficiently charged.
- Use the recovery and firmware requirements specified for this build.
- Flashing incorrectly can cause data loss or bootloops.

## 1. Requirements

- OnePlus 12R (Aston)
- Latest Axion Os ROM package
- Compatible recovery image
- ADB and Fastboot installed
- USB cable and PC

## 2. Clean Flash (Fastboot + ADB Sideload)

1. Reboot your device into bootloader.
2. Flash the required recovery and boot images.
3. Reboot into recovery.
4. Select Apply Update → Apply from ADB.
5. Sideload the Axion Os ROM:

   ```bash
   adb sideload Axion Os-ROM.zip
   ```

6. Perform Format Data / Factory Reset as instructed for this build.
7. Reboot to system.

## 3. Troubleshooting

### ADB Sideload Errors

- Check your USB connection.
- Verify ADB drivers.
- Confirm that you are using a compatible recovery.
- Check the ROM package integrity.

### Bootloop

- Verify firmware compatibility.
- Check whether the correct recovery was used.
- Recheck the clean-flash instructions.

## 4. Credits

- Axion Os Team
- LineageOS Team
- OnePlus 12R Device Maintainers
