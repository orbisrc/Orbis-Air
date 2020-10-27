# Firmware update
- Download and install [DfuSeDemo](https://www.st.com/en/development-tools/stsw-stm32080.html) 
- If you are uploading the firmware for the first time, close the BOOT and 3.3V contacts on the MCU PCB. If you need to update the firmware,  "settings -> info -> DFU mode"
- Connect the board to your computer.
- The jumper between BOOT and 3.3V can be removed
- STM32 download inteface will appear in the device manager
- Run DfuSeDemo



![DfuSeDemo](/image/firmware_update/dfuse_main_screen_w_marks.png)
1. Select "DFU Device in DFU Mode" 
2. Select "Internal flash"
3. Choose target firmware
4. Check "Verify after download"
5. Push button "Upgrade"

- After firmware update, turn off and turn on transmitter