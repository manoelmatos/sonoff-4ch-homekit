
## sonoff 4ch homekit firmware

this is the esp-home-demo example from (https://github.com/maximkulkin/esp-homekit-demo/tree/master/examples/sonoff_basic) extended for the sonoff 4ch device and ready to be flashed

When first run its starts as an AP named "sonoff-4ch", which lets you join your wifi network.

the [firmware](src/firmware/sonoff_4ch.bin) needs to be flashed to 0x4000, rboot is required (see flash.sh)