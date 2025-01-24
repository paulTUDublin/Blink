# Blink

A basic program to "blink" the built-in LED (LD3) on the STM32L432KC attached to PB3 (port B bit 3).
This program includes helper functions (e.g. `pinMode()` and `enablePullUp()` ) that handle the low-level code where registers are accessed directly.