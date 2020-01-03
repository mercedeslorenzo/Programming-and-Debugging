← [Back to Menu](https://telinkgithub.github.io/Telink/ "Menu")
![header-telink](https://i.imgur.com/5kRG6CF.jpg)

Telink Burning and Debugging Tool (BDT) applies to Telink SoCs 8267, 8269, 8266, 8232, 8233, 8366, 8368 and 8x5x series. During SDK development, BDT's functionality includes “Erase flash sector”, “Download firmware”, “Activate MCU when communication failed”, “Access memory space including FLASH /CORE /ANALOG /OTP”, “Read/Write global variable” and “View USB log”.

[Download](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/BDT.zip)

[Tool User guide](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/BDT%20%20User%20Guide.zip)

[Board User guide](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/AN_18010500-E_User%20Guide%20for%20Telink%20Burning%20EVK%20TLSR8266BR56.pdf)

User can follow the guide in this section to download firmware into specific flash space of the target board via “EVK” mode.

__Step 1__: Connect target board with “Burning EVK” via Swire

![Step 1](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/20181020-165920.png)

__Step 2__: Download FW into “FLASH” via “EVK” mode

1. Select chip type of the target board, e.g. 8258 (default option)

2. Select download mode as “EVK”

![Step 2-2](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/20181020-165729.png)

3. Click the “Setting” button to select the offset of flash starting address default at 0

![Step 2-3](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/20181020-165748.png)

4. Select the target firmware file to be downloaded into the target board

![Step 2-4](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/20181020-165813.png)

5. Download the selected file into the target board

![Step 2-5](https://telinkgithub.github.io/Assets/12_Tools-Programming-Debugging/20181020-165831.png)


← [View the Project on GitHub](https://github.com/TelinkGithub/Programming-Debugging)


![footer-telink](https://telinkgithub.github.io/Assets/General/footer.jpg)
