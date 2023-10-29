## Custom-Recovery-Builder For Realme 8

![Realme 8](https://image05.realme.net/general/20210427/1619510447064.png)

|Basic               |Spec Sheet                                                    |
|--                  |--                                                            |
|CPU                 |Octa-core (6x2.0 GHz Cortex-A55 & 2x2.05 GHz Cortex-A76)      |
|Chipset             |MediaTek MT6785 Helio G95                                     |
|GPU                 |ARM Mali-G76 MC4                                              |
|Memory              |4/6GB RAM                                                     |
|Android Version     |11 to 12 (RUI2 to RUI3)                                               |
|Storage             |64/128GB                                                      |
## How To Use Workflow
- Fork this [repository](https://github.com/RipperHybrid/Recovery-Builder).

- Go to Action Tab, and specify all the required values, i.e.;
  - Manifest URL: `https://github.com/minimal-manifest-twrp/platform_manifest_twrp_aosp.git`
  - Manifest Branch: `twrp-12.1`
  - Device Tree: `https://github.com/RipperHybrid/Twrp_Tree.git`
  - Device Tree Branch: `Twrp-12.1`
  - Device Path: `device/realme/RMX3085`
  - Device Name: `RMX3085`
  - Makefile Name: `twrp_RMX3085`
  - Build Target: `recovery`

- Click Run workflow, and wait 'til done.

## Working Feature
- Decryption Date
- Vibration/Haptic 
- Flashing .img/zip
- ADB Sideload
- Terminal/Console
- External Storage (SD and OTG)


## Bugs
- Incorrect Battery Percentage After Decryption
- You Tell Me.

## Device Support Group 
- Telegram Community: https://t.me/Realme8Discussion

## Credits
- https://github.com/TeamWin
- https://github.com/minimal-manifest-twrp
- And to all Contributors in every repositories and scripts I used.
