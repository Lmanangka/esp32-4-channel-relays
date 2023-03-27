# PCB Design for 4-Channel Relays Based on ESP32-WROOM-32 Module

This repository contains the PCB design files, schematic, and 3D model image
for a 4-channel relay board based on the ESP32-WROOM-32 module. The board is
designed for controlling various electronic devices such as light, fans,
motors, and more.

## Features

- Four independently controllable 5V relays.
- ESP32-WROOM-32 module for wireless connectivity and easy programming.
- Terminal block for easy integration to the electronic devices.
- USB TYPE-C connector for power and programming
- Small form factor for easy integration into any project.

## Repository Contents

- **PCB design files**: The KiCad project files for the PCB design.
- **Schematic**: The circuit diagram of the design.
- **3D model image**: A preview image of the 3D model of the board.

## PCB Design

The PCB design is created using KiCad, an open-source software suite for
electronic design automation(EDA). The design files include the Schematic, the
PCB layout, and the Gerber files required for manufacturing.

The board include four 5V relays, each of which is controlled by a GPIO pin of
the ESP32-WROOM-32 module. The module is also responsible for wireless
connectivity and easy programming of the board. Terminal blocks are provided
for easy connection to the electronic devices. The board also includes a USB
TYPE-C connector for power and programming, providing a more robust and
versatile interface than traditional USB connectors.

## Schematic

The Schematic shows the circuit diagram of the design, including the
ESP32-WROOM-32 module, the relays, and the other components of the board.

## 3D Model Image

The 3D model image provides a preview of what the board looks like in a 3D view.
This can be usefule for visualizing the board and how it will fit into your
project.

![3D Model Image](https://github.com/Lmanangka/esp32-4-channel-relays/blob/main/img/3d-model.png?raw=true)

## License

This design is released under the CERN Open Hardware License Version 2 - Permissive.
You are free to use, modify, and distribute the design as long as you include
the license file in your distribution. See the [LICENSE](https://github.com/Lmanangka/esp32-4-channel-relays/blob/main/LICENSE)
file for details.
