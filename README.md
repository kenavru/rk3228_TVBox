# rk3228_TVBox
board MXQ-R2B-LP3, MXQ PRO 4K 5G 

1GB RAM/8GB eMMC
Android 7 (fake 10)

CPU : RK3228A
EMMC+RAM : VNQY 7NA92 JYA42 MICRON
WLAN : 339S0205 WX ES2.1H2T A C

UART : Pins on the other side of CPU, wired as on picture , speed 115200

Same board in other box
https://forum.armbian.com/topic/12656-csc-armbian-for-rk322x-tv-boxes/page/66/#comment-168575


ANDROID backup, Binwalk log in binwalk_android_emmc.txt


ARMBIAN STATUS (https://forum.armbian.com/topic/12656-csc-armbian-for-rk322x-tv-boxes/)

MULTITOOL : Works, but only VIA SSH - no HDMI. Cant use menu via UART. Can do all the job, flash,erase,backup
ARMBIAN IMAGE
LEGACY 4.4 - Works, but no HDMI. Log in LegacyKernelBootLog.txt
Mainline - doesnt work, kernel panic, no HDMI. Log in CurrentKernel.txt
