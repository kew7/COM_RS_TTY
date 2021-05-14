Communications Demonstration


SUMMARY
=======

The COMM sample (TTY) is designed to demonstrate using the Win32 
communications functions while maintaining a common code base with 
Windows code.

MORE INFORMATION
================

The program performs communications using the functions OpenFile, ReadFile, 
SetCommState, SetCommMask, WaitCommEvent, WriteFile, and CloseFile.

Overlapped file I/O techniques are demonstrated.

Usage:

The baud rate, data bits, stop bits, parity, port, RTS/CTS handshaking, 
DTR/DSR handshaking, and XON/XOFF handshaking can be changed under the 
Settings menu item.

Once the communications settings are set, the Action menu item can be 
selected to connect or disconnect the program.

