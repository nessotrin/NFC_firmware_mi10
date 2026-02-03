# NFC firmware for the Xiaomi Mi 10 family
Updated NFC firmware for the Xiaomi Mi 10 family as a Magisk module.

Use with Magisk or modify as you wish. Only 3 files are overwritten. Yes, it's a ZIP. It only contains a binary and two config files.

## Binary from https://github.com/NXP/nfc-NXPNFCC_FW/blob/master/sn1xx/64-bit/libsn100u_fw.so

The config had to be modified with parts of MUNCH as it's invalid for modern firmware. Beware there is a kernel bug around communication with the chip that can cause issues when using an invalid config file. Check my fork and pull request if needed.
