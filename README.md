This project demonstrates how to configure and transmit data over a UART interface using the Intel MRAA library in C++. It is intended for low-level embedded system control where direct hardware communication is required.

## Features

- UART port initialization with baud rate and mode
- Error checking for flow control, parity, and mode configuration
- Sends periodic strings ("Hello Mraa!") over `/dev/ttyS0`
- Gracefully exits using signal interrupt handling (Ctrl+C)
- Cross-platform use possible on devices like Intel Edison, Galileo, UP boards

## Concepts Used

- C++ system programming (signal handling, pointers)
- Embedded I/O abstraction via MRAA
- Serial communication via UART
- Resource management and exception handling
