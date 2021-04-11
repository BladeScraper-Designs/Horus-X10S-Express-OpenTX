
*******************************Release Note******************************************

This Package is for all Archer receiver models except RS. 

Version and Files: 
Archer-X_2.1.6.frsk                            Firmware for all Archer receiver models except RS.
readme.txt                                         Release note 

Firmware Version: v2.1.6

The release firmware resolved the issues below:
--------------------------------------------------------------------------------------------------------------------
1. Added option to support setting whether or not gyro is enabled after failsafe(for SRx receivers & LUA updates needed).
2. Fixed the issue that the default pin assignment for PIN6 was CH1(SR6 only).
3. Fixed a bug where the AUX channel was limited in scope (for SRx receivers).
4. Fixed a bug where OTA upgrades could not be made in redundant state.
5. Fixed an issue with pinmap reset after deleting a receiver bound.
6. Added protection algorithm for self-check mode triggered by mistake in flight.
-------------------------------------------------------------------------------------------------------------------
How to update Archer receiver firmware :

1. Put the firmware under the folder [FIRMWARE] of SD card.
2. Register and bind the receiver with your radio, keep the receiver under working mode. 
3. Find the firmware file in SD folder, select it by press [ENT].
4. Select Flash receiver OTA, re-cycle the receiver power and wait for flash ends.
5. Wait for 5 seconds to have communication recovered ( Version 2.1.5 or above ).
For version below 2.1.5 , Re-cycle the receiver power and wait for 3 seconds to have connection with your radio again.

Note: Receiver is still supported with flashing firmware by s.port wire connection to a radio.
---------------------------------------------------------------------------------------------------------------------
More details please check FrSky website.
https://www.frsky-rc.com/product-category/receivers/2-4ghz-access/archer-series/

**********************All rights reserved to FrSky Electronic ., Ltd.*********************************
