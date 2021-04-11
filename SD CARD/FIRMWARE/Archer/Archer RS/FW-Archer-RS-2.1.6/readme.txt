
*******************************Release Note******************************************

This Package is for Archer RS firmware update. 

Version and Files: 
Archer-RS_2.1.6.frsk                          Firmware for Archer RS receiver.
readme.txt                                         Release note 

Firmware Version: v2.1.6

The release firmware resolved the issues below:
--------------------------------------------------------------------------------------------------------------------
Added support for 4ms Racing Mode
 
Note：
1. In RacingMode, the register/binding are not supported and there is no telemetry feedback.
2. Racing mode is not supported to be turned On/Off during use when used in conjunction with flight control.
After the mode switch, the receiver should be repowered otherwise the flight control output will jitter due to different signal cycles. 
3. Module & radio firmwares need to be upgraded at the same time.
-------------------------------------------------------------------------------------------------------------------
How to update Archer receiver firmware :
1. Put the firmware under the folder [FIRMWARE] of SD card.
2. Register and bind the receiver with your radio, keep the receiver under working mode. 
3. Find the firmware file in SD folder, select it by press [ENT].
4. Select Flash receiver OTA, re-cycle the receiver power and wait for flash ends.
5. Re-cycle the receiver power and wait for 3 seconds to have connection with your radio again.

Note: Receiver is still supported with flashing firmware by s.port wire connection to a radio.
---------------------------------------------------------------------------------------------------------------------
More details please check FrSky website.
https://www.frsky-rc.com/product-category/receivers/2-4ghz-access/archer-series/

**********************All rights reserved to FrSky Electronic ., Ltd.*********************************
