# Proiect_TSC

![Diagrama_Block_Openbook drawio](https://github.com/user-attachments/assets/68c5a4ed-2c58-4e37-9742-be7280558ab6)

BOM (Bill of Materials):

| Item | Product Link | Datasheet Link |
|------|-------------|---------------|
| 112A-TAAR-R03 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://store.comet.bg/download-file.php?id=27596) |
| BD5229G-TR | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://datasheet.datasheetarchive.com/originals/distributors/Datasheets_SAMA/f2b9741ef86007909f138d561a359946.pdf) |
| Capacitor 0402 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://componentsearchengine.com/Datasheets/2/CC0402MRX5R5BB106.pdf) |
| CPH3225A | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/CPH3225A/Seiko%20Instruments/datasheet/) |
| DS3231SN RTC | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/DS3231SN%23/Analog%20Devices/datasheet/) |
| ESP32 WROVER 0805 Capacitor | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://ro.mouser.com/datasheet/2/40/schottky-3165252.pdf) |
| ESP32 WROVER BME680 Sensor | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/BME680/Bosch%20Sensortec/datasheet/) |
| ESP32 WROVER MCP73831 Power Management | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://eu.mouser.com/datasheet/2/268/MCP73831_Family_Data_Sheet_DS20001984H-3441711.pdf) |
| ESP32 WROVER P-Channel MOSFET | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.diodes.com/assets/Datasheets/DMG2305UX.pdf) |
| ESP32C6 Varistor 1812 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.tdk-electronics.tdk.com/inf/75/db/CTVS_14/Surge_protection_series.pdf) |
| ESP32-C6 WROOM-1-N8 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/ESP32-C6-WROOM-1-N8/Espressif%20Systems/datasheet/) |
| FH34SRJ-24S-0.5SH Connector | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.hirose.com/en/product/document?clcode=CL0580-1255-6-99&productname=FH34SRJ-24S-0.5SH(99)&series=FH34SRJ&documenttype=2DDrawing&lang=en&documentid=0000990903) |
| LED Chip 0603 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/KP-1608SURCK/Kingbright/datasheet/) |
| MAX17048G+T10 Battery Fuel Gauge | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/MAX17048G+T10/Analog%20Devices/datasheet/) |
| MBR0530 Schottky Diode | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/MBR0530/ON%20Semiconductor/datasheet/) |
| PGB1010603MR Inductor | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/PGB1010603MR/Littelfuse%20Inc./datasheet/) |
| QWIIC Connector | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.youtube.com/watch?v=dQw4w9WgXcQ) |
| RCL CPOL 3528 | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://s3.amazonaws.com/snapeda/datasheet/TAJB475K025RNJ_AVX.pdf) |
| SI1308EDL-T1-GE3 MOSFET | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.youtube.com/watch?v=dQw4w9WgXcQ) |
| SJ | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.youtube.com/watch?v=dQw4w9WgXcQ) |
| TPTP20R | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://easyeda.com/component/7524403feb2642ac9f9f26dfb93ceacf) |
| USB4110-GF-A USB Hub | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://gct.co/files/drawings/usb4110.pdf) |
| USBLC6-2SC6Y USB Surge Protection | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://www.snapeda.com/parts/USBLC6-2SC6Y/STMicroelectronics/datasheet/) |
| XC6220A331MR-G Voltage Regulator | [Product](https://store.comet.srl.ro/Catalogue/Product/43497/) | [Datasheet](https://product.torexsemi.com/system/files/series/xc6220.pdf) |

  Hardware Components:

  ESP32-C3-WROOM:
    
    Wi-Fi/BLE connectivity
    Supports SPI, I2C, and UART communication
    Operates at 3.3V, powered by an LDO regulator

  USB-C - Charging & USB communication
  
  MCP73832 - LiPo battery charging management
  
  LDO 3.3V - Supplies power to ESP32 and peripherals
  
  DC/DC 5V - Provides 5V for sensors
  
  BME680 - Enveroment sensor

ESP32 PINOUT:

    IO0 - RTC INT Signal
    IO1 - CLOCK Signal
    IO2 - SPI MISO Signal
    IO3 - EPD BUSY Signal
    IO4 - SD Card Chip Select
    IO5 - EPD DC Signal
    IO6 - SPI SCK Signal
    IO7 - SPI MOSI Signal
    IO9 - BOOT Button Signal
    IO10 - EPD Chip Select
    IO11 - Flash NOR Memory Chip Select
    IO12 - USB D+ Signal
    IO13 - USB D- Signal
    IO15 - CHANGE Button Signal
    GPIO16 - UART TX
    GPIO17 - UART RX
    IO18 - RTC RESET Signal
    IO19 - I2C Sensor VDDIO Signal
    IO20 - EPD 3V3
    IO21 - I2C SDA Signal
    IO22 - I2C SCL Signal
    IO23 - EPD RESET Signal

Note : On the final 3D models i did not render the top and buttom ground planes because the working pc did not have the power to render them
