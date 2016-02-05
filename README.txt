PIC32-RETROBSD is OSHW board based on PIC32-Pinguino-MICRO modification with PIC32MX795F512H processor and RetroBSD bootloader. The board comes loaded with bootloader and RetroBSD.

You need to prepare a microSD card with the latest file system. It is always recommended to use the files from the RetroBSD's web-site.

The default file system (that we use here to prepare the microSD cards that we sell) can be downloaded using the torrent in folder "Default binaries/Stable-Release" - "RETROBSD_filesystem_v2.torrent".

If you want to update the firmware without a programmer use a mini USB cable and compatible software (for example, pic32prog). You would need to enter bootloader mode. Typically, press button BUT and then RST button. If you have one of the boards that were released early (they had an improper bootloader) - connect pin 14 (RD8) and pin 20 (GND) of CON1 together and then press and release the RST key. 

If you want to restore the bootloader and RETROBSD firmware and you have a hardware tool -> use the binary "BOOT+RETRDOBSD3.hex" from folder "Default binaries/Stable-Release". You would need a programmer tool like PIC-KIT3 and adapter for the small 6-pin ICSP connector (0.05" step).

If you are looking for the latest software sources - the best idea would be to visit the RETROBSD web-site and forum.