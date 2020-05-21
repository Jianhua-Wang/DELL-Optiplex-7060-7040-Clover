# DELL Optiplex 7060 EFI

## General Information

### Hardware Information

- i5-8700
- UHD 630
- 16G RAM (2400MHz and 2133MHZ, and works fine)
- 1T HDD (windows) + 512Gb WD Blue SDD (MacOS)
- Sapphire rx 560D 4G
- Wi-Fi & Bluetooth: BCM94360CD
- Display: Dual 1080P 24 inch display

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gf04k0jfbzj30gb09vmz2.jpg)

### Software

- MacOS 10.14.6 (did not try Catalina)
- Clover

## Result:

- Display: one DP, not support dual DP
- Ethernet card: :ok:
- Sound card: Speaker is OK, but line-out has some trouble

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gf04n5gmooj30ga0bjaav.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlly1gf04lw0dqdj30a70d8jtp.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf04r8du67j30890ab43e.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf04rttekoj308k08otcz.jpg)

## Tips:

- UHD630 can only support one display for most case
- DP to HDMI not work for hackintosh
- Radeon r7 340/240/250 graphic card (device ID: 6611) cannot be driven in 10.14 or higher version (video memory: 7Mb).
- Radeon rx 560D from mingying is not driver-free, while sapphire's AMD card works fine!
- If you are using a AMD driver-free graphic card, replace the config.plist with confing-amd.plist.