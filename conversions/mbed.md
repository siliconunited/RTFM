# MBED Conversion Manual
> This document should contain any information regarding the converting to or from MBED style libraries.

# Convert Arduino Project to MBED
1. Understand the functions in the Arduino library.
2. Maths and logic are mostly the same, but keep in mind that the Arduino is 8/16bit.
3. All the different protocols will need to be rewritten for the MBED.
4. The `.pde` file will most likely be your `main.cpp`. `setup()` will go above with your declarations, `loop()` will be in int `main()`.
- Note: Do not use `setup()` and `loop()`, but for `loop()` use while
5. To start add `mbed.h` (this is a quick and dirty way) and try to compile, then solve the errors as you go.
6. Run across a problem you can't solve. Visit https://developer.mbed.org/forum/mbed/ and post the issue.

# Resources
- [MBED Forums](https://developer.mbed.org/forum/mbed/)
