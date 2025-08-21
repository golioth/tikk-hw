# Tikk Bluetooth Sensor / Output Board

We created the Tikk board as an affordable* board ($15 in low volume) for displaying the capabilities of Golioth's Bluetooth Connectivity. It plugs into a low cost ($3) Tenstar Robot nRF52840 breakout board, targeted at Keybord makers. We will have many of these nodes surrounding a Golioth gateway to showcase all of the uplink and downlink functions available to users. The focus was on easily demonstrated functions, such as LEDs and motor drivings for outputs and various in-tree Zephyr supported sensors for inputs.

## Rev A Preview Image

<img width="1065" height="790" alt="image" src="https://github.com/user-attachments/assets/0c14e370-f6f7-42d6-848e-2969a301d85a" />
<img width="1065" height="790" alt="image" src="https://github.com/user-attachments/assets/c60096c8-5a74-4f4e-b107-caa7a1c17b56" />

## Rev A Photos


![Tikk-RevA-Back](https://github.com/user-attachments/assets/e2f5e6e8-561b-4076-9a82-f85a306ee780)

![Tikk-RevA-Front](https://github.com/user-attachments/assets/cbd65eea-25ac-4e51-bfeb-36c983a40843)


## Features

This board has the following characteristics when soldered to something like the Tenstar Promicro

* 105 LEDs in 0402 format, individually addressable in a 7x15 matrix with the IS31FL3731
* Two H-Bridge chips (L9110S) for driving a single stepper or two dc motors
* 3 axis accelerometer (LIS2DH12)
* Temperature sensor (TMP102)
* QWIIC / Stemma header to expand breakout boards*
* User button
* Reset button
* A voltage divider that monitors battery voltage

Additional capabilities added by the Tenstar ProMicro and nRF52840

* Additional GPIOs I can solder to (5 digital, one analog)
* LiPo battery charger on board
* Load switch for all peripherals except motor driver
* USB Input to the nRF52840 (get serial terminal using USB-CDC)
* NFC tag emulation (via the nRF52840 and onboard flex connector)
