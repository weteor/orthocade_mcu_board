# orthocade series mcu board

this is a mcu daughterboard used for some keyboards from the orthocade series, namely [Dig Dug](https://github.com/weteor/DigDug), [Brk Out](https://github.com/weteor/BrkOut) and [Froggr](https://github.com/weteor/Froggr).

## Want/Need one?

production files can be found [here](./prod). The cases are designed for 1.2mm pcbs, but also work with  1.6mm pcbs without problems.



You will need the following parts to build one:

- 1x capacitor - 0805 - 100nF

- 3x resistor -  0805 - 10kOhm

- 1x PCA9555 or TCA9555 IO-Expander

- 1x 20pin 0.5mm pitch FCC/FCP Connector

- 1x either Seeed Xiao RP2040 or Seeed Xiao BLE controller

optionally if you want to use BLE w/ battery:

- 1x battery connectro 2pin Molex Pico Blade
- 1x on/off switch MSK-12C02

### firmware

The SPC EVDR uses ZMK firmware.

If you prefer the github workflow, you can find the zmk config [here](https://github.com/weteor/SPC_EVDR-Config).

### 

![side](img/side.png)![back](img/back.png)![render](https://user-images.githubusercontent.com/79446655/197630217-8b76d6c4-c2ee-4cee-82ff-70f0dda0aa4b.mp4)
