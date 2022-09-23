# Dell-Inspiron_7560_Hackintosh_Opencore
Dell Inspiron 7560 Hackintosh(Latest version of Big Sur) EFI, replace wireless network card with DW1560

OpenCore Version 0.6.4 | EFI modified based on [ashishcomputing/Dell-Inspiron-7560-Hackintosh-Opencore](https://github.com/ashishcomputing/Dell-Inspiron-7560-Hackintosh-Opencore)

To use this EFI,you need to use macrecovery.py to download recover image and place `BaseSystem.dmg` and `BaseSystem.chunklist` to `./com.apple.recovery.boot` of your USB Drive

**You also need replace wireless network card with DW1560**

download script:

```shell
python macrecovery.py -b Mac-E43C1C25D4880AD6 -m 00000000000000000 download
```

last, to login your apple ID,you need change your SN and etc. with `GenSMBIOS` or `OCAT ` tool

to fix ComboJack issue, you may try ComboJack  Fix with [ashishcomputing/Dell-Inspiron-7560-Hackintosh-Opencore](https://github.com/ashishcomputing/Dell-Inspiron-7560-Hackintosh-Opencore)
