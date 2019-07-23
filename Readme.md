GPLV2 licensed replacement keyboard PCBs.

# Omnikey 
Requires an Teensy++ 2.0 controller. - Firmware at https://github.com/qmk/qmk_firmware/tree/master/keyboards/omnikeyish

## Changelog

#### 1.3
* Nav cluster to Numpad cluster distance was off by 1/32 of an inch (0.7935mm). Meassurement confirmed on two original Omnikey PCBs and Plus rev3 plate. Not quite sure how I managed to assemble the first board.
* Rev1/3 Mounting holes got jumbled up in Schematic Reorganisation. Fixed now.

#### 1.1
* Teensy++ 2.0 uses pin D6 for an LED, so that interfers with the ROW5 assignment used on 1.0 boards. Moved ROW5 to pin E6

# AT101
Requires an Teensy 2.0 controller 

## Changelog

### 1.1
* Nav and numeric cluster distances to the alpha block were off by 1/32 inch.
* Big Arse Enter footprint updated, so stabiliser hole is large enough.
