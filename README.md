# BinaryIO
A simple library to aid in writing to / reading from binary files in C++ using `iostream`. Includes necessary functions to save various types of data to files in binary format.

To use the library, simply include 'BinaryIO.h' and you will be good to go; it is a small library and only relies on `std::string` and `iostream`.

## Functions

The file contains functions that allow a programmer to save data based on its _size_; you can save 1, 2, or 4 bytes at a time (8/16/32 bit), and allows you to save strings of ASCII text up to 65,356 characters long. They are all saved by using unsigned chars (`uint8_t, uint16_t, uint32_t` for 8, 16, and 32 bits, respectively).
