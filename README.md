# Telefunken-TLKE3214D-IR-codes
IR codes for Led TV 32'' Telefunken TLKE3214D

Protocol: NEC
Address: 0xBF00
Commands below

Measured remote control with an Arduino UNO using [IrRemote](https://github.com/Arduino-IRremote/Arduino-IRremote) library.
Also added more commands that are not on the default remote control. Those command where also found using the same library.

+------------+------------+-----------+
| Header 1   | Header 2   | Header 3  |
+============+============+===========+
| body row 1 | column 2   | column 3  |
+------------+------------+-----------+
| body row 2 | Cells may span columns.|
+------------+------------+-----------+
| body row 3 | Cells may  | - Cells   |
+------------+ span rows. | - contain |
| body row 4 |            | - blocks. |
+------------+------------+-----------+

