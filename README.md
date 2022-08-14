# QT-Servo
Easily connect up to four servos to your Adafruit QT Py or Seeed Xiao with this tiny little board.

## Controlling Servos with your QT Py or Xiao

The Adafruit QT Py line of development boards and the Seeed Xiao module are very small microcontroller boards that are fantastic for building projects requirnig a lot of microcontroller power packed into a tiny amount of space. These development boards are great for providing exactly this mix of diminutive size and powerful capabilities. However, because of their tiny size, it can be difficult to connect all the external systems and components your project might require.
The **QT Servo** board provides a convenient interface for connecting up to four servos to your QT Py or Xiao. The servos are controlled by the four analog inputs provided on these boards (pins A0 to A3). In addition to the servo connections, the board also accepts external 5V power that can run the servos with a higher current capacity than the QT Py or Xiao alone can provide. The external power input also powers the boards themselves. Because of the small size of the QT Servo board, the power inputs are soldered directly to the PCB.
On the software side, you can control servos connected to the QT Servo the same way you would if you connected the servos directly to the QT Py or Xiao. You can use the Arduino Servo library and specify the control pins to correspond to the PINs on the QT Servo board.
