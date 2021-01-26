<<<<<<< HEAD
# uQuad-FC

[WIP] A simple ATMega328p-based flight controller for small quadcopters. Compatible with the classic MultiWii software for Arduino-based flight controllers.

The two versions, given by the 5V one and the 3.3V one, correspond to different receiver voltages. Unless you plan on using a Spektrum satellite receiver or the like, use the 5V version.

Parts: most components are standard; for example, any I2C MPU6050 module should work with the broken-out I2C header. There is a standard 6-pin serial connection which can be used with a FTDI USB-to-serial programmer to flash firmware.

MOSFET selection for the motor drivers is quite flexible -- anything in a SOT-23-3 package should work. Make sure the desired MOSFET can handle the rated current -- upwards of 8A per MOSFET should be fine with most standard sized brushed DC motors, eg 8520 size and smaller.
=======
# uQuad-FC

[WIP] A simple ATMega328p-based flight controller for small quadcopters. Compatible with the classic MultiWii software for Arduino-based flight controllers.

Design goals: as small as possible while allowing all parts to be (relatively) easily hand-soldered.

The two versions, given by the 5V one and the 3.3V one, correspond to different receiver voltages. Unless you plan on using a Spektrum satellite receiver or the like, use the 5V version. The flight controller is configurable to use a serial or PPM receiver.

Parts: most components are standard; for example, any I2C MPU6050 module should work with the broken-out I2C header. There is a standard 6-pin serial connection which can be used with a FTDI USB-to-serial programmer to flash firmware.

MOSFET selection for the motor drivers is quite flexible -- anything in a SOT-23-3 package should work. Make sure the desired MOSFET can handle the rated current -- upwards of 8A per MOSFET should be fine with 8520 brushed motors, for instance.
>>>>>>> 36ca620858e47b417366f62f882f4eaa48ba6be0
