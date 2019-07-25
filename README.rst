.. _lvgl-sample:

LittlevGL Basic Sample
######################

Overview
********

This sample application displays "Hello World" in the center of the screen
and a counter at the bottom which increments every second.

Requirements
************

- `nRF52-DK`_
- `ILI9341 2.2" SPI TFT Display Module 240x320`_

Wiring
******

The nRF52-DK should be connected as follows to the
ILI9341 TFT display.

+-------------+----------------+
| | nRF52-DK  | | ILI9341 TFT  |
| | Pin       | | Pin          |
+=============+================+
| P0.25       | SCK            |
+-------------+----------------+
| P0.17       | D/C            |
+-------------+----------------+
| P0.21       | RST            |
+-------------+----------------+
| P0.23       | MOSI           |
+-------------+----------------+
| P0.24       | MISO           |
+-------------+----------------+
| P0.16       | CS             |
+-------------+----------------+

Building and Running
********************

Build this sample using the following commands:

.. zephyr-app-commands::
   :zephyr-app: samples/gui/lvgl_nrf52_pca10040_ili9341
   :board: nrf52_pca10040
   :goals: build
   :compact:

See :ref:`nrf52_pca10040` on how to flash the build.

References
**********
