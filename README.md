# X-Pander 3
## Introduction

The heir-apparent to the CMD EX-3 and EX2+1, the X-Pander 3 opens up a wealth of expansion options for your Commodore 64, SX64, C128, or  C128D. Utilize multiple cartridges at once, or easily switch cartridges without removal. The X-Pander 3 offers the following features:

- 3 individually-selectable expansion ports
- power indicators for each port
- Ability to swap IO select lines on 2nd and 3rd ports
- easily accessed piano-style configuration switches
- top-loading or back-loading 3rd port.
- 3rd port can accommodate 2 cartridges at the same time*
- reset switch

\* Both top and back-loading options for port 3 share a single set of configuration switches, requiring 2 cartridges that can coexist without configuration.

## Requirements

- Commodore C64, C64C, C128, C128D, or SX64

## Purchase

PS/2 Encoder models can be purchased at the [RETRO Innovations Online Store](http://store.go4retro.com/products/X%2dPander-3-Slot-Cartridge-Port-Expander.html).

## Technical Details

X-Pander 3 creates a “passive” cartridge port “bus”, with switches on the following lines:

- Power (2 switches)
- IO1 ($de00-$deff)
- IO2 ($df00-$dfff)
- ROML ($8000)
- ROMH ($a000)
- EXROM
- GAME

Additionally, ports 2 and 3 contain jumpers allowing one to “swap”  IO1 and IO2. This can be used to move a peripheral cartridge (like a  serial card or ethernet card) normally residing at IO2 to the  alternative IO1 position so that it can coexist with the RAM Expansion  Unit, which must reside in IO2. Jumpers are provided, but the jumper  pins can be removed and replaced with a subminiature DPDT (double pole,  doub;e throw) switch.

## Support

The unit works exactly like the Creative Micro Designs EX3 (EX2+1)  units, so instructions for those units will work equally well with the  X-Pander3.  Our thanks to Carsten Jensen for creating the [X-Pander3 User’s Manual](http://www.go4retro.com/downloads/X-Pander3/X-Pander3_Manual.pdf).

Expansion port cartridges were not normally designed to coexist with  other cartridges. Thus, it is impossible to detail the nearly infinite  combinations and whether each works or not. Also, since the “bus”  places additional load on the unbuffered expansion port IO lines,  cartridges that are susceptible to signal degradation may not work with  X-Pander 3, even when installed alone.

Some helpful hints:

- Always insert or remove X-Pander 3 with the system port off
- Clean cartridge contacts before installation
- Switches are “on” when depressed. Normally, all switches can be left in the “on” position
- IO1/IO2 swap jumpers must be moved as a pair
- While the X-Pander 3 will work with the SX64, its use is discouraged. Unlike the other C64-compatible systems, the SX64 uses a ribbon cable to  connect the top loading expansion port with the main system PCB. Ribbon cable degrades signals badly, and can render X-Pander-3 unusable.