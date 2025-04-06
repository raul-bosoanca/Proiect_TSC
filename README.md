# Proiect_TSC

![Diagrama_Block_Openbook drawio](https://github.com/user-attachments/assets/68c5a4ed-2c58-4e37-9742-be7280558ab6)

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
