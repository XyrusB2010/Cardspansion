# Cardspansion-ESP
This is the second MCU to be implemented into the Cardspansion series. Featuring an ESP32-WROOM-32UE, it is suited for applications requiring wireless connectivity (Wi-Fi and/or BLE). Because the ESP32 has no need for an 8MHz crystal, this card should have a simpler design. Unlike the STM32U5, it also comes with a different set of features (JTAG & SPI). Please note that this board does not directly interface USB due to the lack of a controller in the MCU.
## Features
- I2C
- UART
- SPI
- JTAG
- I2S (including support for input)
- 2 LEDs (broken out for carrier board)
