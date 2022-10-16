# xpad-ce-rebuild
Rebuild xpad kernel module for COREELEC, for some "cheap" xinput compatible game controller supported.

> Game controller tested:
> DAQI S2 Pro
> NewGame Q1 Pro

Source Code: https://github.com/paroj/xpad/tree/2c087f90bb85799df02400f6f10ccdca70e02c6e

Only tested in ce-20, built with toolchain in ce-20.

## Usage

Download files to somewhere, and add lines below in `autostart.sh`

```
rmmod xpad
insmod {your path}/xpad.ko
```
