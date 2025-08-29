# Cardspansion-RPI
The Cardspansion-RPI is the 4th and final MCU to be added to the first generation of the Cardspansion series. It is reccomended to use the Waveshare RP2350-Tiny board, but the RP2040-Tiny is also compatible, at the cost of losing UART, I2C, and LEDs (Will be fixed in a later revision). If you do use the RP2350-Tiny, you also gain access to the SPI, I2S and USB interfaces. The RP2350 and RP2040 have a dedicated USB header on board, but you will need an FPC breakout in order to use it. Just like the Cardspansion-NRF, the Raspberry Pi board is very large, so the silkscreen text on the front layer has to be placed on the side.
## Features
- I2C (RP2350 only)
- UART (RP2350 only)
- SPI
- USB-OTG functionality (Host on dedicated USB pin, OTG configured on PIO)
- 2 LEDs (broken out for carrier board)
## PCB Render
<img width="857" height="857" alt="cardspansion-rpi-front" src="https://github.com/user-attachments/assets/0bcce19a-db84-419b-85b5-4fe161d57de5" />
<img width="857" height="857" alt="cardspansion-rpi-back" src="https://github.com/user-attachments/assets/d0ed0264-b3bd-47cb-afa0-ba778946dc21" />
