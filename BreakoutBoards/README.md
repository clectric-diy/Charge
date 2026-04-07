# Breakout Boards

This directory contains small, focused hardware modules for common controls and interfaces used in synth and embedded builds.

## Modules

- [DaisySeed](DaisySeed/): a carrier for the Daisy Seed module, which is the main microcontroller "brain" that runs your synth code and controls everything else.
- [Encoder](Encoder/): rotary knob input module; an encoder lets you turn endlessly to move through values, menus, or parameters.
- [Encoder_RGB](Encoder_RGB/): rotary encoder plus RGB LEDs; you get one control that can both adjust settings and show visual state by color.
- [LED_RGB](LED_RGB/): RGB indicator light module for 3.3V systems; useful for showing mode, status, level ranges, or activity.
- [MicroSD](MicroSD/): storage interface module; a microSD breakout lets your project read/write files like presets, samples, or logs.
- [Potentiometer](Potentiometer/): classic analog knob input; a potentiometer gives a direct position value (for example 0-100%).
- [Potentiometer_RGB-3.3V](Potentiometer_RGB-3.3V/): potentiometer plus RGB LED in one module, combining hands-on control with immediate visual feedback.
- [USB_TypeC](USB_TypeC/): general USB Type-C connection module for bringing power and, when designed in, USB data into your project.
- [USB_TypeC_PowerOnly](USB_TypeC_PowerOnly/): simplified USB Type-C power-input module when you only need power, not USB data.
- [WS2811](WS2811/): addressable LED driver module; WS2811 lets a controller set LED color with a serial data signal (NeoPixel-style behavior).
