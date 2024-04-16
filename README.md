# Implementation of a machine learning algorithm on an esp32 using the BME688

In this repository you will find the different files used for implementing a machine learning algorithm made by bosch using the adafruit/Bosch BME688 sensor:
More explanations on how to use the files here: https://docs.google.com/document/d/1Vs_w_9rIWZzF76EOs_i_H5kShtdvldttZDzdsQ-DgS0/edit?usp=sharing

**None of the files here have been developped by me, I only modified them.** 

### This repository is structured as follow:

**src**: contains all sources files of the different steps of the project\
* **read_values**: simple code to read values from the BM688 with only the LED code that has been removed for my usage and the modification of the I2C address from LOW to HIGH (0x76 to 0x77).\
* **bosch_exemple**: exemple provided by bosch for detecting the presence of a hand sanitizer with only the LED code that has been removed for my usage and the modification of the I2C address from LOW to HIGH (0x76 to 0x77).\
* **simplified_use**: modified version of the bosch_exemple to only generate an alert if a certain class is reaching a threshold.\

**lib**: contains the zip files of the libraries I used at the time I made this project.\
