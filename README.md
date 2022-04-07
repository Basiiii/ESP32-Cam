# ESP32-Cam
Testing use of ESP32-Cam AI Thinker module.

# Using Visual Studio Code
- Install extension of ESP-IDF.
- Driver instalation:
Open ESP-IDF/components folder, open PowerShell and run:
```
git clone https://github.com/espressif/esp32-camera
```

- Open PowerShell within folder and run:
```
code .
```

- Connect ESP32 module.

- Open config tool - RTCIO config - Tick "Support array 'rtc_gpio_desc' for ESP32
- Open config tool - ESP32 Specific - Tick "Support for external, SPI-connected RAM'

- Select serial port with extension. Then use ESP-IDF extension to build, flash and open serial monitor.
