# MQTT-ACCEL

This application is derived from the mqtt-simple sample from Nordic Semiconductor nRF Connect SDK

mqtt-simple sample: https://github.com/nrfconnect/sdk-nrf/tree/master/samples/nrf9160/mqtt_simple

nrf Connect SDK license: https://github.com/nrfconnect/sdk-nrf/blob/master/LICENSE

## Overview

This application runs on Nordic Semiconductor's Thingy91. Takes samples from the Thingy91's accelerometer
(ADXL362) and sends them to a preconfigured MQTT server topic.
All configuration is handled in the file `prj.conf` to be included at compile time.
See Nordic Semiconductor's SDK and Zephyr OS documentation for details on how to run this application.

