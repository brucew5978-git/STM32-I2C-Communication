# STM32-I2C-Communication

## Description 
General intro into I2C communication on STM32 Nucleo L476RG

Scope: Successful communication via I2C, but need more driver building for getting proper sensor values

### Notes
Serial display can use following steps:
1. ls /dev/tty.*
2. find stm32 device (usually usbmodemxxxx)
3. open new terminal window and "screen /dev/tty.usbmodemXXXX 115200"

Serial ports management:
1. screen -ls (See which nodes are active)
2. "screen -XS 78xx quit"

### Sources
Tutorial: https://www.digikey.ca/en/maker/projects/getting-started-with-stm32-i2c-example/ba8c2bfef2024654b5dd10012425fa23?utm_adgroup=General&utm_source=google&utm_medium=cpc&utm_campaign=Dynamic%20Search_EN_RLSA_Buyers&utm_term=&productid=&utm_content=General&utm_id=go_cmp-206206025_adg-17000358065_ad-399612148256_aud-506470258530:dsa-19959388920_dev-c_ext-_prd-_sig-CjwKCAiA6byqBhAWEiwAnGCA4PC7b2pjJRj0wx87hQbVLG4Y80oZlV4aXhHnVPL7yI4g1AGv4PlBJhoC9_kQAvD_BwE&gad_source=1&gclid=CjwKCAiA6byqBhAWEiwAnGCA4PC7b2pjJRj0wx87hQbVLG4Y80oZlV4aXhHnVPL7yI4g1AGv4PlBJhoC9_kQAvD_BwE
Datasheet: https://www.renesas.com/us/en/document/dst/isl29125-datasheet
STM-Duino Driver: https://github.com/sparkfun/SparkFun_ISL29125_Breakout_Arduino_Library
