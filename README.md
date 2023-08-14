# Module with LTR390 chip for measuring ambient light and ultraviolet radiation

Is there a lot of light in the room or not enough and do I need to turn the lights on? Just use our LTR390 sensor module to measure ambient light and ultraviolet radiation and you'll know right away? And what to do next? Use it for example in your home automation and automatically switch the lighting on.

![Assembled module](https://github.com/LaskaKit/LTR390-UV-Sensor/blob/main/img/4.jpg)

The LTR390 sensor is located on our standard size and dimension module, where you will find [two uŠup connectors](https://blog.laskakit.cz/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-%CE%BCsup/) and also a place to male/female header with a standard 2.54mm pitch. From the uSup connector you can conveniently connect the module with LTR390 to other modules and development boards. 

And what another modules you can use? For example the sensor [SCD41 for measurement of CO2, temperature and humidity](https://www.laskakit.cz/laskakit-scd41-senzor-co2--teploty-a-vlhkosti-vzduchu/), sensor SHT41 [temperature nad humidity](https://www.laskakit.cz/laskakit-sht40-senzor-teploty-a-vlhkosti-vzduchu/) and [sensor of pressure, temperature, humidity BME280](https://www.laskakit.cz/arduino-senzor-tlaku--teploty-a-vlhkosti-bme280/), [RTC - Real Time Clock](https://www.laskakit.cz/laskakit-ds3231-orig--rtc-hodiny-realneho-casu/) with DS3231 or [OLED display with 1.3" dimension and 128x64px resolution](https://www.laskakit.cz/laskakit-oled-displej-128x64-1-3--i2c/?variantId=11903).

You can connect all these modules also to our evaluation boards such as [Meteo Mini with solar panel input](https://www.laskakit.cz/laskakit-meteo-mini/?variantId=10473), easily programmed [ESP32-DEVKit](https://www.laskakit.cz/laskakit-esp32-devkit/?variantId=11481), super [low power and small ESP32-C3 LPKit](https://www.laskakit.cz/laskkit-esp-12-board/?variantId=10482), [ESPInk with ESP32 and huge 4.2" ePaper](https://www.laskakit.cz/laskakit-espink-42-esp32-e-paper-pcb-antenna/?variantId=11400) or [popular eval board with ESP32 and 3.5" TFT display](https://www.laskakit.cz/laskakit-espd-35-esp32-3-5-tft-ili9488-touch/?variantId=12158). 

Finally, it is not necessary to use only our eval boards, you can use [common Arduino boards](https://www.laskakit.cz/arduino-2/), single-board computers as [Rock Pi or Raspberry Pi](https://www.laskakit.cz/mini-pc/) or another popular evaluation boards.

![Bottom side of module](https://github.com/LaskaKit/LTR390-UV-Sensor/blob/main/img/02027.jpg)

The power supply voltage of the module and also the sensor is from 1.7V up to 3.6V. The sensor address is 0x53.
On the front side you will find a solder bridge that connects the mounted pull-up resistors to the I2C bus. 

Supported libraries in Arduino IDE
[https://github.com/levkovigor/LTR390](https://github.com/levkovigor/LTR390)
[https://github.com/adafruit/Adafruit_LTR390](https://github.com/adafruit/Adafruit_LTR390)

Our example codes are available on [https://github.com/LaskaKit/LTR390-UV-Sensor/tree/main/SW](https://github.com/LaskaKit/LTR390-UV-Sensor/tree/main/SW)
