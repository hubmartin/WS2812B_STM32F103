# LowMEM WS2812b library ( WS2812B_STM32F103 )
This is a memory and CPU efficient implementation of WS2812B library for STM32F1xx processors.

**See my other repositories for F0 and F3, F4 port where the library and implementation is explained in details.**

https://github.com/hubmartin/WS2812B_STM32F4
https://github.com/hubmartin/WS2812B_STM32F3

**You have to compile it with -Og or at least -O1 optimizations to take advantage of it.**

This version/port was created in Eclipse IDE, but you can simply call **make** in the **Debug** folder and compile the sources.

The only board with STM32F103 I had was on the ST-link Discovery debugger, so I reflashed the debugger and set the WS2812b outputs on PA2 and PA3.

