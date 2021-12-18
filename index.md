### Microcontroller
First of all, you'll need a microcontroller as the brains for your proto! Some good options are:
* [esp32](https://www.aliexpress.com/item/32858054775.html) - (recommended) this is what I use, 240MHz dual core processor, built in bluetooth and wifi, plenty of ram and storage. If you want to run my code, you'll need this one or similar.
* [Teensy](https://www.pjrc.com/teensy/) - super beefy specs, but no wifi. Honestly kind of overkill for just driving some matrices and led strips, but some people like them.
* [Arduino nano](https://www.aliexpress.com/item/4000046641724.html) - simple, cheap, and 5v logic so no level shifters needed. Slow compared to the others, and not a lot of ram or storage. Still enough for simple code and storing a few faces.

### Matrices
For the matrices you basically have two options, either one should work fine:
* [Max7219](https://www.aliexpress.com/item/32667345173.html), can be found on aliexpress, need to be soldered together or look for the [2](https://www.aliexpress.com/item/4001062318048.html) and [4](https://www.aliexpress.com/item/4000313326546.html) matrix variants that come as one piece. If you use a 3.3v microcontroller like the esp32 you will need a [level shifter](https://www.aliexpress.com/item/1972789887.html) to talk to them, since they expect 5v signals and can become unreliable and glitchy on 3.3v. This won't be necessary if you use a 5v microcontroller like the arduino nano.
* [Adafruit](https://www.adafruit.com/product/1052) matrices, only come in single and [2 matrix](https://www.adafruit.com/product/2037) variants so a little sanding and cutting is required for the 4 matrix mouth parts. They're a little easier to code for, but much more expensive than the Max7219 option. I don't run these, but my friend does and he did not need a level shifter to make them work reliably.

### Cheek/fin leds
For the cheekpanels/fins you'll need:
* [Led rings](https://www.aliexpress.com/item/32953186414.html) - 2x8, 2x12, 2x16. These sit behind the cheek panels and make them all glowy and stuff.
* [Led strip](https://www.aliexpress.com/item/2036819167.html) - go with 144 leds/m to ensure the individual leds aren't visible behind the diffuser. These go in the fins.
* [Led diffuser film](https://www.aliexpress.com/item/4000420311000.html) or something like plexiglass which you can sand, to diffuse the leds in the cheekpanels and fins

### Other
You'll also want to get:
* A 40mm 5v [fan](https://www.amazon.com/Noctua-NF-A4x20-5V-3-Pin-Premium/dp/B072Q3CMRW). This noctua one is nice because it will be inside the head and needs to be as quiet as possible while still providing decent airflow.

Other tools / items that will come in handy, in case you don't have them yet:
* [Wire](https://www.aliexpress.com/item/33015915354.html) - 6 colors, on rolls in a handy little box
* [TS100](https://www.aliexpress.com/item/32860309312.html) - A really nice portable soldering iron. Honestly, any soldering iron will do but life is better when it's not *too* cheap.
* Solder
* Wire cutter / stripper
* Connectors and corresponding crimp tool (optional, in case you don't want to direct solder everything, but recommended)
* [XT-30](https://www.aliexpress.com/item/4000388530012.html) connectors for power, [USB-C](https://www.aliexpress.com/item/1005001337982060.html) or [micro usb](https://www.aliexpress.com/item/32827910858.html) breakout boards for easy connection to a usb power bank.
* [Double sided tape](https://www.aliexpress.com/item/4000631036937.html) to hold the led rings and mounting pieces in place

If you want to sand and paint the prints ([here](https://www.youtube.com/watch?v=0vgynnYzo08) is a pretty good example) you'll need:
* Sandpaper, from coarse to really fine grit to get a good surface finish
* Filler/primer
* Paint in your favorite color(s)


All links given above are just examples, and if you don't want to wait too long for shipping I'd recommend looking somewhere other than aliexpress, but I don't know what would be a good option for you.
