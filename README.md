# STM32-RF
---------------------------------- STM32RF board ----------------------------------------

The board contains an STM32 microcontroller, an RF transceiver, and an antenna interface as well as a USB full-speed interface

* The idea of the board is to be used in a system where data is sent over the air. The data is received by the antenna and processed in the microcontroller then sent out to a host computer via the USB interface.

* Design:
    - We can divide the parts of my system/board into 3 parts: the RF part (receive data), The microcontroller part (processing data), and the USB part (communicate data with a PC).

* The design was made in Kicad 6
