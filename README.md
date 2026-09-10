Day 1 of Building Hackpad
September 10, 2026

I got started with KiCad today to build my Hackpad. The first hurdle was installing the custom Hack Club “care package” libraries. It took me a moment to realize that footprints and symbols are managed in two separate library managers, but I eventually linked the .sym and .pretty files globally.

After that, I jumped into the schematic editor. I placed the SEEEDUINO-XIAO (which will be the brain of the board) and three push buttons. At first, I made a rookie mistake by wiring a pin straight to ground without the switch in between, but I caught it and fixed it. Now pins 9, 10, and 11 are wired properly through the switches and tied to a common ground. Everything is electrically connected and safely saved.
