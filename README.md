# 1.8 TFT DISPLAY WITH ESP32 AND PLATFORM.IO

This small project is a basic example to setup a TFT display.

I bought this one from az-delivery and although they supplied some examples I could not get it to work.

https://www.az-delivery.de/nl/products/1-8-zoll-spi-tft-display?variant=4982039773211

I searched the internet and found a lot of resources but none did match my setup and did not work.

Finally with the help of a combination of tutorials I got my setup working.

# hardware

ESP32-WROOM-32 (ALI-EXPRESS)

# pin mapping

|TFT    |ESP32     |
|-------|----------|
| LED   |   V5     |
| SCK   |   D27    |
| SDA   |   D14    |
| A0    |   D12    |
| RESET |(not used)|
| CS    |   D13    |
| GND   |   GND    |
| VCC   |   3V3    |