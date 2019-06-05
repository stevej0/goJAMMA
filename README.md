# goJAMMA
Game on JAMMA development board PROTOTYPE v0.2 (C) 2019 Steve Jones / BONEYARD

This is a prototype FPGA based JAMMA board for the development of homebrew games for arcade machine platforms and superguns.

The design is currently in a prototype stage, pretty much everything has been tested as working, however bugs and performance issues may remain. This design is NOT approved for production as of yet, but the files are made public as an aid to others developing their own hardware.
  
FAQ to follow...
  
  
Hardware specifications (fixed):

Altera MAX10 10M25SAE FPGA, 25K logic elements, extended Flash features  
1MB 8Bit Static RAM, 10ns access  
16MB 8Bit HyperRAM, 166Mhz DDR, 128 byte burst  
48Mhz Crystal clock oscillator  
microSD card interface  
ADC 4 channel, 10 bit analog to digital convertor (Analog inputs via expansion connector)  
Buffered video output  
Stereo audio amplifier, 11 Watts  
PCM5101 Stereo 12S DAC  
4 Way Dip Switch  
Standard JAMMA 5v tolerant inputs, plus configuration jumpers for 6-button Pandoras Box style interface  
1x USER button, 1x RESET button  
1x USER LED  
Large long-life and user replacable through hole capacitors in the audio and voltage regulator sections  
  
  
Homebrew logic core (basic wishlist) specifications, likely to change:
  
CPU core (undecided, but a 6502 at 4Mhz currently works well)  
256 Colour palette, 320 x 240 pixel framebuffer (double buffered)  
Sprites (undecided, most likely a blitter for the framebuffer with fast HyperRAM as gfx data source)  
Layers (undecided, at least one text overlay, maybe a tiled background layer also)  
16 channel sample playback  
Ability to load programs and data from microSD fat32 formatted cards  



