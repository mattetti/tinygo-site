---
title: "Drivers"
chapter: true
weight: 90
---

# Drivers

TinyGo has driver support for 33 different sensors and devices such as digital accelerometers and multicolor LEDs.

All of the drivers code is in the TinyGo Drivers repository located at [https://github.com/tinygo-org/drivers/](https://github.com/tinygo-org/drivers/).

| Device Name | Interface Type |
|----------|-------------|
| [ADXL345 accelerometer](http://www.analog.com/media/en/technical-documentation/data-sheets/ADXL345.pdf) | I2C |
| [APA102 RGB LED](https://cdn-shop.adafruit.com/product-files/2343/APA102C.pdf) | SPI |
| [AT24CX 2-wire serial EEPROM](https://www.openimpulse.com/blog/wp-content/uploads/wpsc/downloadables/24C32-Datasheet.pdf) | I2C |
| [BH1750 ambient light sensor](https://www.mouser.com/ds/2/348/bh1750fvi-e-186247.pdf) | I2C |
| [BlinkM RGB LED](http://thingm.com/fileadmin/thingm/downloads/BlinkM_datasheet.pdf) | I2C |
| [BME280 humidity/pressure sensor](https://cdn-shop.adafruit.com/datasheets/BST-BME280_DS001-10.pdf) | I2C |
| [BMP180 barometer](https://cdn-shop.adafruit.com/datasheets/BST-BMP180-DS000-09.pdf) | I2C |
| [Buzzer](https://en.wikipedia.org/wiki/Buzzer#Piezoelectric) | GPIO |
| [DS1307 real time clock](https://datasheets.maximintegrated.com/en/ds/DS1307.pdf) | I2C |
| [DS3231 real time clock](https://datasheets.maximintegrated.com/en/ds/DS3231.pdf) | I2C |
| ["Easystepper" stepper motor controller](https://en.wikipedia.org/wiki/Stepper_motor) | GPIO |
| [ESP8266/ESP32 AT Command set for WiFi/TCP/UDP](https://github.com/espressif/esp32-at) | UART |
| [GPS module](https://www.u-blox.com/en/product/neo-6-series) | I2C/UART |
| [HUB75 RGB led matrix](https://cdn-learn.adafruit.com/downloads/pdf/32x16-32x32-rgb-led-matrix.pdf) | SPI |
| [LIS3DH accelerometer](https://www.st.com/resource/en/datasheet/lis3dh.pdf) | I2C |
| [LSM6DS3 accelerometer](https://www.st.com/resource/en/datasheet/lsm6ds3.pdf) | I2C |
| [MAG3110 magnetometer](https://www.nxp.com/docs/en/data-sheet/MAG3110.pdf) | I2C |
| [BBC micro:bit LED matrix](https://github.com/bbcmicrobit/hardware/blob/master/SCH_BBC-Microbit_V1.3B.pdf) | GPIO |
| [Microphone - PDM](https://cdn-learn.adafruit.com/assets/assets/000/049/977/original/MP34DT01-M.pdf) | I2S/PDM |
| [MMA8653 accelerometer](https://www.nxp.com/docs/en/data-sheet/MMA8653FC.pdf) | I2C |
| [MPU6050 accelerometer/gyroscope](https://store.invensense.com/datasheets/invensense/MPU-6050_DataSheet_V3%204.pdf) | I2C |
| [PCD8544 display](http://eia.udg.edu/~forest/PCD8544_1.pdf) | SPI |
| [SHT3x Digital Humidity Sensor](https://www.sensirion.com/fileadmin/user_upload/customers/sensirion/Dokumente/0_Datasheets/Humidity/Sensirion_Humidity_Sensors_SHT3x_Datasheet_digital.pdf) | I2C |
| [SSD1306 OLED display](https://cdn-shop.adafruit.com/datasheets/SSD1306.pdf) | I2C / SPI |
| [SSD1331 TFT color display](https://www.crystalfontz.com/controllers/SolomonSystech/SSD1331/381/) | SPI |
| [ST7735 TFT color display](https://www.crystalfontz.com/controllers/Sitronix/ST7735R/319/) | SPI |
| [ST7789 TFT color display](https://cdn-shop.adafruit.com/product-files/3787/3787_tft_QT154H2201__________20190228182902.pdf) | SPI |
| [Thermistor](https://www.farnell.com/datasheets/33552.pdf) | ADC |
| [VEML6070 UV light sensor](https://www.vishay.com/docs/84277/veml6070.pdf) | I2C |
| [VL53L1X time-of-flight distance sensor](https://www.st.com/resource/en/datasheet/vl53l1x.pdf) | I2C |
| [Waveshare 2.13" e-paper display](https://www.waveshare.com/w/upload/e/e6/2.13inch_e-Paper_Datasheet.pdf) | SPI |
| [Waveshare 2.13" (B & C) e-paper display](https://www.waveshare.com/w/upload/d/d3/2.13inch-e-paper-b-Specification.pdf) | SPI |
| [WS2812 RGB LED](https://cdn-shop.adafruit.com/datasheets/WS2812.pdf) | GPIO |

We also give you the ability to add new drivers. If your device isn't listed here, please raise an issue in the [issue tracker](https://github.com/tinygo-org/drivers/issues).
