# CO2 Sensor

<img src="photo.webp" height="400">

[esphome](https://esphome.io/) configuration for a Co2 sensor based on the Wemos S2 mini and the Senseair S8 sensor. Publishes the results to Home Assistant via MQTT and displays on a OLED display. The OLED display shows the current ppm CO2 value, and a small graph to show the trend over the last 15 minutes.


## [See configuration](co2-sensor.yaml)

Note: This configuration includes a light entity for controlling a single WS2812B LED. You can remove this if you don't need it.

## 3D Printed Case

Available for free at [printables.com](https://www.printables.com/model/692296-senseair-s8-co2-wemos-oled-shield-enclosure).

## License

[2-Clause BSD License](./LICENSE.md)
