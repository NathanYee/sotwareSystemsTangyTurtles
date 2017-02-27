# Arduino Synthesizer

A team repository for the class Software Systems at Olin College of Engineering for the team Tangy Turtles.

## Description

We have created an Arduino synthesizer that can be commanded to play a series of tones from an input file that specifies the frequency and duration of each sequential tone. The tones are played through a simple 1-bit DAC, which low-pass filters the output of the Arduino's PWM signals to create smooth waveforms.

## Authors

Shane Kelly, Carl Moser, Nathan Yee

## Resources

* [1-bit DAC and wave generation in C.](http://makezine.com/projects/make-35/advanced-arduino-sound-synthesis/)
* [Serial communications on an Arduino in C.](https://www.appelsiini.net/2011/simple-usart-with-avr-libc)
* [Arduino port registers.](https://www.arduino.cc/en/Reference/PortManipulation)

## Usage

Compile the Arduino code and upload it to the Uno.

`SOMETHING ABOUT AVR-DUDE PROBABLY`

Once the Arduino code has been uploaded, send the desired song file to the serial port that the Arduino is currently connected to.

`make && ./stdinToSerial -f little_lamb.txt -p /dev/ttyACM0`

## License

**MIT License**

See `LICENSE.txt`.
