# MU100-DIT

A modification for Yamaha synthesizers to add optical audio out.

This mod has been especially designed for: 
* Yamaha MU100
* Yamaha MU100R
* Yamaha MU90
* Yamaha MU90R

For these synths, a connector board has been designed that enables this mod to be installed with little-to-no board modification.

On the MU100/MU90, this involves soldering an unpopulated header and bridging some pads.

On the Rackmount versions of these, the MU100R/MU90R, this will plug in directly to the molex connector for the analog board, no board modification required:
![photo_2022-07-17_12-39-27](https://user-images.githubusercontent.com/69168929/179422151-2c272ed4-4cb8-4a8d-a61d-f0a968ebf39f.jpg)

The main board has been designed to fit within the limited back panel space on the MU100/MU90 and to not run into the MU100/MU100R's expansion cards.
![photo_2022-07-17_12-47-33](https://user-images.githubusercontent.com/69168929/179422331-9be33bff-7ec6-4d38-8f06-b7241b7882f0.jpg)

## Schematics:

**TODO**

## Installation instructions:

**TODO**

## Other compatible synths
This includes the following synthesizers:

* Yamaha MU128
* Yamaha AN200

...and many others. This mod will work for any device that has a 16-bit, 18-bit, 20-bit, or 24-bit PCM/I2S data stream feeding into the DAC, and has a consistent sample rate of 32/44.1/48/88.2/96khz. If you would like to test this out on other devices, please feel free to submit a pull request detailing what device and what settings you set.

## Links:
* https://esher.ru/blog/887.html - The main inspiration for this design, special thanks to vetal!
* https://github.com/vetal-esher/18bit-DIT - Vetal's custom AK4103A board that is designed to use coax with a transformer instead of optical.
* https://kurohane.net/wiki/index.php?SC-88Pro%E3%81%AB%E5%85%89%E3%83%87%E3%82%B8%E3%82%BF%E3%83%AB%E5%87%BA%E5%8A%9B%E3%82%92%E4%BB%98%E3%81%91%E3%82%8B (Japanese) - Another AK4103A optical mod, designed for the SC-88 pro.
* https://github.com/w-dee/AK4103A-DIT - Another, general purpose AK4103A DIT modification.
