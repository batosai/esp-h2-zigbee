# ESP32-H2 Demo Zigbee Device

This project is a demo Zigbee device based on the ESP32-H2 / ESP32-C6

## Features

- [x] Binary input

## Hardware

- [ESP32-H2](https://www.espressif.com/en/products/socs/h2/overview)

## GPIO

| GPIO   | Function              |
| ------ | --------------------- |
| GPIO12 | Binary input (Button) |

## Init var env

. $HOME/esp/esp-idf/export.sh

## Build

idf.py build

## Flash

idf.py -p PORT flash

## Monit

idf.py -p PORT monitor