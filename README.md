PAL (Peripheral Abstraction Layer)
=================

This is an attempt at privinding a more or less standard interface to peripherals that are commonly found in MCUs.

I expect this to eventually function similar to how MBED and/or Arduino work, in that you simply specify a atarget device and the functions magically work, but that's a good ways away.

For now, the implementation will only focus on the TI's Tiva MCUs (due to being incredibly familiar with them already), then move on to SiLab MCUs (EFM32, maybe even C8051Fxx).
