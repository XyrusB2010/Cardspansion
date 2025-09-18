# Cardspansion-Dev
This is the first carrier board for the Cardspansion series. It breaks out all of the supported interfaces of the cardspansion-gen1 series (including SDIO, I2S, JTAG, SPI, SWDIO, I2C, and UART). The board also features a CR2032 battery holder for RTC. A DC barrel jack is included, and can handle a voltage up to 12V. Unlike Arduino UNOs, there is a manual switch for selecting the voltage source between USB and DC. The board has 6 LEDs, which indicate power, user LEDs, and UART signals. Most of the components are SMD, except for the DC barrel jack. At the top centre, two push buttons are included for BOOT and RESET, which most MCUs use. PLEASE DO NOT power the board via the 5V pins, as they will damage the onboard voltage regulators. This dev board may be forwards compatible with following generations, although features exclusive to other generations will not be fully compatible. 
## Features
- Supports cardspansion-gen1 cards
- All cardspansion-gen1 interfaces broken out
- Onboard CR2032 battery holder for RTC
- External DC source supported (6-12V)
- Physical slide switch for 5V voltage source (DC Jack, USB)
- LEDs for 3.3V, 5V, 2 User LEDs, UART
- Push buttons for RESET and BOOT
## PCB Render
<img height="850" alt="cardspansion-dev-front" src="https://github.com/user-attachments/assets/24166001-d1f4-4490-bc51-ecfb1c87e6d2" />
<img height="850" alt="cardspansion-dev-back" src="https://github.com/user-attachments/assets/091b6e3d-286b-486f-a86f-4415c13d25da" />

