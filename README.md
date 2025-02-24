# LDARC_F411-B2_firmware

This repo is to store the custom betaflight firmware for the LDARC F411-B2 drone firmware. If you messed yours up, or if it arrived without any firmware, you may have noticed that the manual provides only a broken link to the proper firmware target (F411-B2-BF3.5.6-2021-03-29-a.hex). I used the STM32CubeProgrammer to dump the firmware on the board I got, and now share it here for anyone to use. No promises of success are given, but if you have and LDARC F411-B2 I bet this will work for you. 

Since I pulled this directly off the board, it is a .bin instead of a .hex. You will need to use the cube programmer to flash your board. I used the following guide to dump the firmware; see the bottom section "Restoring Data" to flash onto your board.

https://oscarliang.com/backup-fc-stm32cubeprogrammer/#Download

Good luck!
