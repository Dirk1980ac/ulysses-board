# The Ulysses Board
This is a Raspberry Pi I/O expansion Board.

# Features

* All I/Os presented to the outside world are shielded
* Power regulation (Takes input from 9V to 30V)
* Backpower
* Firmware EEPROM (ID EEPROM)
* Configuration EEPROM
* Event log EEPROM
* 8 Control buttons
* I²C LC-Display
* 6 Status LEDs
* Real-time-clock w/ buffer battery
* "Tamper detection" circuit (Logs if someone opens the device while it is in workiung state)
* RS-232 serial interface
* 2 CAN busses (CAN_1 and CAN_2)
* 4 ADC inputs (with Voltage dividers)
* 16 digital IOs (programmable w/pull-ups)
* I²C EEPROM programming socke
* SPI EEPROM programming socke
* I²C breakout (3,3V / 5V selectable)

# Limitations

* No SPI breakout as we are already using 4 chips on the SPI bus.
* DIO 0/1 GPIOs  are 3,3V only (at least for now)

# Information
This is a work in progress. ans changes are to be expected. A PCB layout and additional software will be added as time goes by.<br><br>
This Board is intented to be an external developer I/O board.<br><br>
<strong>Attention: </strong> This is NOT a HAT form factor board and never will be.<br>


# Copyright
Copyright ©2022 by Dirk Gottschalk

# License
This project is provided as is under the terms and conditions of the GNU General Public License (GNU GPL) version 2 ONLY.
