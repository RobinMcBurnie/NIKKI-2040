# NIKKI-2040
A TFL-Microcontrollers off-line command word based remote control device running on the RP2040

This project is intended to create a voice controller as an assistive device. The device is intended to work as an "off-line" assistant that does not require an internet connection.
The final unit will use a combination of (local) WiFi and IR to send control messages to any device to be controlled. Initially this is a TiVo box and the TV it is connected to, plus possibly a bedside lamp.

The model is intended to run on an RP2040 chip, with the audio data being supplied preprocessed into a tensor representing a Mel Spectrogram by a RPi Pico W (possibly Pico 2 W) board.

The project is split into separate parts. These will be added as they are ready for presentation.
