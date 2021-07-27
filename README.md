# 0

## Goal
This project is about creating simple http server publishing car parameters that can be read over diagnostic port.
User will have possibility to get/set car parameters that can be rach over diagnostic port.

# Users
End user will be a person who opens exposed http server and get/set car parameters through GUI.

## Supported cars
Fiat Coupe 1997

## Supported diagnostic interfaces
TBD

## Hardware platform
Raspberry PI 3 B+
https://www.raspberrypi.org/products/raspberry-pi-3-model-b-plus/
https://datasheets.raspberrypi.org/rpi3/raspberry-pi-3-b-plus-product-brief.pdf

## Software platform
TBD, Raspberry PI OS?

## Programming language
Python, node js, C, C++?

## Product architecture
The goal is to group the most common car parameters into the table and based on that create abstraction layer between http server and different cars/interfaces.

Id|Car parameter name|Marke|Common parameter name|Output format|
- |-                 |-    |       -             |     -       |
0 |Water temperature |Fiat Coupe|Engine Water temperature|%f|
