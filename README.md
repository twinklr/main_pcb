# Twinklr Main Board

This repository contains layouts for the Twinklr main PCB in EAGLE's `brd` and `sch` formats. Gerber files are also included.

## `twinklr_board`

This was the original Twinklr board with a built-in 1W amplifier. Unfortunately, it doesn't really work very well, so the amplifier was removed from the final version.

## `twinklr_board_5v`

This is the board used in the current version of Twinklr. It distributes 5V from a tip-negative PSU to the Raspberry Pi, rather than stepping down 9V with a regulator. It has no amplifier.

## License  

Twinklr is Open Hardware.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img
alt="Creative Commons License" style="border-width:0"
src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br /><span
xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Twinklr</span> by
<span xmlns:cc="http://creativecommons.org/ns#"
property="cc:attributionName">Tom Armitage and Richard Birkin</span> is Open
Hardware. It is licensed under a <a rel="license"
href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons
Attribution-ShareAlike 4.0 International License</a>  
If you use any work in this project, you should credit us, and you must
republish any changes you make under the same license. This license does permit
commercial use of these designs, but consider getting in touch before selling
anything.  
