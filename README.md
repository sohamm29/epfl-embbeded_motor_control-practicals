# Embedded Motor Control Labs

Stores all the code ad reports created within the context of the MICRO-510 Class

---

## Setup

In your console, open in the directory where you would like to store this  repository, and run the commands below:

```bash
git clone git@github.com:sohamm29/epfl-embbeded_motor_control-practicals.git
git checkout dev

```

---

### Overview

| Exercise | Description |
| -------- | --------- |
| **1.1** | Setting up STM32CubeMX Extensions for VSCode and for appropriate microcontroller |
| **1.2** | Turning a LED on and off, get a feel of different pins and GPIO on the board |
| **1.3** | Generate a interrupter at 20kHz Frequency |
| **1.4** | Configure PINS and the Analog-Digital-Converter (ADC). Then Using the Above, get current signal value on each interrupt and blink LED on or off |
| **1.5** | Generate a PWM Signal using interrupt at 20kHz, and a Catch/Compare Register to threshold duty cycle |
| **2.1** | Establish a current flow through motor with a transistor on/off system **below** Motor |
| **2.2** | Establish a current flow through motor with a transistor on/off system **above** Motor, with Bootstrapping |
| **2.3** | Using two transistors, one above and one below (TBD)  |
| **3.1** | Set up synchronous rectification and PWM duty cycle manipulation on diff H-bridge branches to get motor moving |
| **3.2** | Manipulate both diagonal transistors in H-bridge with PWM, called PWM Double  |
| **3.3** | Manipulate only one transistor in diagonal, the other is always on, called PWM Simple |
| **3.4** | Use all 4 transistors in PWM Simple format, and adapt potentiometer duty cycle scaling and switching to turn motor in both directions |
