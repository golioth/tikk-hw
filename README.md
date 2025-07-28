# Tikk Bluetooth Sensor / Output Board

We created the Tikk board as an affordable* board ($15 in low volume) for displaying the capabilities of Golioth's Bluetooth Connectivity. It plugs into a low cost ($3) Tenstar Robot nRF52840 breakout board, targeted at Keybord makers. We hope to have many of these boards surrounding a Golioth gateway to showcase all of the uplink and downlink functions available to users. The focus was on easily demonstrated functions, such as LEDs and motor drivings for outputs and sensors for inputs.

## Rev A Preview Image

<img width="1065" height="790" alt="image" src="https://github.com/user-attachments/assets/0c14e370-f6f7-42d6-848e-2969a301d85a" />
<img width="1065" height="790" alt="image" src="https://github.com/user-attachments/assets/c60096c8-5a74-4f4e-b107-caa7a1c17b56" />



## Features

This board has the following characteristics

* 105 LEDs, individually addressable in a 7x15 format (0402 LEDs)
* Two HBridge chips for driving a single stepper or two dc motors
* 3 axis accelerometer (LIS2DH12)
* NFC input
* TMP102 temperature sensor
* QWIIC header to expand breakout boards
* User button
* Reset button
* Additional GPIOs I can solder to (5 digital, one analog)
* A voltage divider that monitors battery voltage 
* The bluetooth chip is an nRF52840
* LiPo battery charger on board
* Load switch for all peripherals except motor driver
* USB Input to the nRF52840
