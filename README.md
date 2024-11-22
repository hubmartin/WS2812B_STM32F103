# LowMEM WS2812b library ( WS2812B_STM32F103 )
This is a memory and CPU efficient implementation of WS2812B library for STM32F1xx processors.

## STM32F103 Benchmark
 * 10 paralel WS2812B outputs @ 72 MHz
 * **16 paralel WS2812B outputs** @ 128 MHz (overlocked)

**See my other repositories for L0, F3 and F4 port where the library and implementation is explained in details.**

https://github.com/hubmartin/WS2812B_STM32F4
https://github.com/hubmartin/WS2812B_STM32F3

**You have to compile it with -Og or at least -O1 optimizations to take advantage of it.**

This version/port was created in Eclipse IDE, but you can simply call **make** in the **Debug** folder and compile the sources.

The only board with STM32F103 I had was on the ST-link Discovery debugger, so I reflashed the debugger and set the WS2812b outputs on PA2 and PA3.

