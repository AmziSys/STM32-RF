# STM32-RF
---------------------------------- STM32RF board ----------------------------------------

* Intro:
  The idea of the board is to be used in a system where data is sent over the air. The data is received by the antenna and processed in the microcontroller then sent out to a host computer via the USB interface.

* Design:
  The board contains:
  - STM32L432KBU6: STM32 microcontroller
  - nRF24L01P: 2.4GHz RF transceiver suitable for ultra-low power wireless applications (ISM band)
  - Power supply: USB, ESD protection, Fuse, and LDO regulator
  - Antenna interface and its matching circuit
  - R and C

During the design process, the system/board was divided into 3 parts: the RF part (receive data), The microcontroller part (processing data), and the USB part (communicate data with a PC).
In general, anything RF needs to be in 4 layers. So, the front layer will be used for signals, the inner-cooper-layer 1 will be ground (GND), the Inner-cooper-layer 2 will be power (or 3.3V), and the bottom copper layer will be used for signals.

* The design was made in Kicad 6
