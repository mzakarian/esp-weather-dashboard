# esp-weather-dashboard
Weather Dashboard on ESP32 using [ESPHOME](https://esphome.io)

## Description

This templates creates a simple Dashboard displaying various sensor readings collected from 
[Homeassistant](https://www.home-assistant.io) in a paginated slideshow on a (very) small 
0.96 inch display (SH1106 128x64). 

The following information are being displayed:

- current time
- thermal writings
- air quality (co2)
- pressure
- humidity
- battery status

## Usage with Python

1. Install ESPHome - `pip3 install esphome`
2. Install Dependencies - `pip3 install pillow tornado esptool`
3. Validate the configuration, create a binary, upload it, and start MQTT logs. - `esphome weather_dashboard.yaml run`

## Sources

### Related Docs

- [Getting Started with ESPHome](https://esphome.io/guides/getting_started_command_line.html)
- [Cookbook: Time & Temperature on OLED Display](https://esphome.io/cookbook/display_time_temp_oled.html)
- [SSD1306 OLED Display](https://esphome.io/components/display/ssd1306.html)
- [Home Assistant Sensor](https://esphome.io/components/sensor/homeassistant.html)

### Fonts

- [Open Sans - Designed by Steve Matteson](https://fonts.google.com/specimen/Open+Sans?preview.text_type=custom)

### Images

- [Material Design icons](https://material.io/resources/icons/?style=baseline)
