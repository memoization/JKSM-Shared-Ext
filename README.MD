# JKSM for 3DS
JKSM or JK's Save Manager for 3DS.
* Dump and Restore save data for 3DS titles
* Dump and Restore extra data for 3DS titles
* Dump and Restore data for system titles
* Dump and Restore Boss extra data
* Set Play Coins to any amount 300 or lower

This is checked branch from commit https://github.com/J-D-K/JKSM/commit/7a37c23c89134df8fd1f6508944c45725f14.

**See [releases](https://github.com/memoization/JKSM-Shared-Ext/releases) for the built files.**

## Building:
* Setup [devkitPro](https://www.3dbrew.org/wiki/Setting_up_Development_Environment)
* Run this command. You may need to remove `dkp`:
	* `dkp-pacman -S 3ds-curl 3ds-libjson-c 3ds-mbedtls 3ds-zlib`
* Run *build-elf.bat* then run *build-rom.bat* for the cia file.
