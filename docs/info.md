<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

An SPI-controlled PWM peripheral. The design operates at **10 MHz** and uses SPI communication at **\~100 KHz** to configure registers that control output enables, PWM enables, and duty cycles. The system comprises two main modules: an **SPI Peripheral** for register management and a **PWM Peripheral** for signal generation.

## How to test

cd test/
make -B

## External hardware

- fpga
- SPI peripheral
