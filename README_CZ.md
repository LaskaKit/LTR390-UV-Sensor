# Modul s čipem LTR390 pro měření okolního osvětlení a ultrafialového záření

Je v místnosti hodně světla nebo málo a je potřeba rozsvítit? Stačí použít náš modul s čidlem LTR390 pro měření okolního osvětlení a ultrafialového záření a víš to hned? A co s tím dál? Využij to třeba v tvé domácí automatizaci a automaticky spínej osvětlení.

![Osazený modul](https://github.com/LaskaKit/LTR390-UV-Sensor/blob/main/img/4.jpg)

Čidlo LTR390 je umístěno na naší u standardní velikosti a rozměru modulu, kde najdeš dva [uŠup konektor](https://blog.laskakit.cz/predstavujeme-univerzalni-konektor-pro-propojeni-modulu-a-cidel-%CE%BCsup/)y a také místo pro zapájení standardního hřebínku s roztečí 2.54mm. </br>
Tento modul tak můžeš pohodlně propojit s dalšími moduly.</br>
Z uŠup konektoru tak pohodlně připojíš modul s LTR390 do dalších modulů a vývojových desek. </br>

A jaké moduly to jsou? Třeba čidlo [SCD41 pro měření CO2, teploty a vlhkosti vzduchu](https://www.laskakit.cz/laskakit-scd41-senzor-co2--teploty-a-vlhkosti-vzduchu/), čidla SHT41 [teploty a vlhkosti vzduchu](https://www.laskakit.cz/laskakit-sht40-senzor-teploty-a-vlhkosti-vzduchu/) a [čidla tlaku, teploty a vlhkosti vzduchu BME280](https://www.laskakit.cz/arduino-senzor-tlaku--teploty-a-vlhkosti-bme280/), [RTC Hodiny reálného času](https://www.laskakit.cz/laskakit-ds3231-orig--rtc-hodiny-realneho-casu/) s DS3231 nebo [OLED displej o velikosti 1.3" a rozlišení 128x64px](https://www.laskakit.cz/laskakit-oled-displej-128x64-1-3--i2c/?variantId=11903).

Připojit to můžeš nejen do našich vývojových kitů jako jsou univerzální [Meteo Mini s možností připojení solárního panelu](https://www.laskakit.cz/laskakit-meteo-mini/?variantId=10473), jednoduše programovatelný [ESP32-DEVKit](https://www.laskakit.cz/laskakit-esp32-devkit/?variantId=11481), velmi [úsporný a malý kit ESP32-C3 LPKit](https://www.laskakit.cz/laskkit-esp-12-board/?variantId=10482), [ESPInk s ESP32 a velkým 4.2" ePaper](https://www.laskakit.cz/laskakit-espink-42-esp32-e-paper-pcb-antenna/?variantId=11400) nebo [populárním kitem s ESP32 a 3.5" TFT displejem](https://www.laskakit.cz/laskakit-espd-35-esp32-3-5-tft-ili9488-touch/?variantId=12158). 

Nakonec, není nutné používat pouze naše desky - použít [můžeš téměř kterékoliv Arduino](https://www.laskakit.cz/arduino-2/), jednodeskový počítač [Rock Pi nebo Raspberry Pi](https://www.laskakit.cz/mini-pc/) či jiné vývojové kity s I2C sběrnicí.

![Zadní strana osazeného modulu](https://github.com/LaskaKit/LTR390-UV-Sensor/blob/main/img/02027.jpg)

Napájecí napětí modulu a tedy i čidla je od 1.7V až do 3.6V. Adresa čidla je 0x53.
Na přední straně najdeš pájecí most, který připojuje osazené pull-up rezistory na I2C sběrnici. 

## Tento modul si můžeš objednat na https://www.laskakit.cz/laskakit-ltr390-uv-senzor/

Podoporovaná knihovna v Arduino IDE
[https://github.com/levkovigor/LTR390](https://github.com/levkovigor/LTR390)
[https://github.com/adafruit/Adafruit_LTR390](https://github.com/adafruit/Adafruit_LTR390)

Naše vzorové kódy najdeš na [https://github.com/LaskaKit/LTR390-UV-Sensor/tree/main/SW](https://github.com/LaskaKit/LTR390-UV-Sensor/tree/main/SW)
