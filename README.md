# AVR8js

JavaScript implementation of the AVR 8-bit architecture

[![Build Status](https://travis-ci.org/wokwi/avr8js.png?branch=master)](https://travis-ci.org/wokwi/avr8js)
[![NPM Version](https://img.shields.io/npm/v/avr8js)](https://www.npmjs.com/package/avr8js)
![License: MIT](https://img.shields.io/npm/l/avr8js)
![Types: TypeScript](https://img.shields.io/npm/types/avr8js)
[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/wokwi/avr8js)

## Running the demo project

The demo project allows you to edit Arduino code, compile it, and run it in the simulator.
It also simulates 2 LEDs connected to pins 12 and 13 (PB4 and PB5). 

To run the demo project, check out this repository, run `npm install` and then `npm start`.

### Walkthrough Video Tutorial

A step-by-step video tutorial showing how to build a simple Arduino simulator using AVR8js and React:

[![AVR8JS Walkthrough Video](https://i.imgur.com/3meSd1m.png)](https://youtu.be/fArqj-USmjA)

### Unofficial examples

* [Minimal Example](https://stackblitz.com/edit/avr8js-minimal?file=main.ts)
* [6 LEDs](https://stackblitz.com/edit/avr8js-6leds?file=index.ts)
* [LED PWM](https://stackblitz.com/edit/avr8js-pwm?file=index.ts)
* [Serial Monitor](https://stackblitz.com/edit/avr8js-serial?file=index.ts)
* [NeoPixel Matrix](https://stackblitz.com/edit/avr8js-ws2812?file=index.ts)
* [Arduino MEGA NeoPixel Matrix](https://stackblitz.com/edit/avr8js-mega-ws2812?file=index.ts)
* [Simon Game](https://stackblitz.com/edit/avr8js-simon-game?file=index.ts) - with pushbuttons and sound
* [XMAS LEDs](https://stackblitz.com/edit/avr8js-xmas-dafna?file=index.ts)
* [Assembly Code](https://stackblitz.com/edit/avr8js-asm?file=index.ts)
* [EEPROM persistence](https://stackblitz.com/edit/avr8js-eeprom-localstorage?file=eeprom-localstorage-backend.ts)

## Which chips can be simulated?

The library focuses on simulating the *ATmega328p*, which is the MCU used by the Arduino Uno.

However, the code is built in a modular way, and is highly configurable, making it possible
to simulate many chips from the AVR8 family, such as the ATmega2560 and the ATtiny series:

* [ATtiny85 Simulation](https://avr8js-attiny85.stackblitz.io?file=index.ts)

Check out [issue 67](https://github.com/wokwi/avr8js/issues/67#issuecomment-728121667) and
[issue 73](https://github.com/wokwi/avr8js/issues/73#issuecomment-743740477) for more information.

## Running the tests

Run the tests once:

```
npm test
```

Run the tests of the files you modified since last commit (watch mode):

```
npm run test:watch
```

For more information, please check the [Contributing Guide](CONTRIBUTING.md).

## License

Copyright (C) 2019, 2020, 2021 Uri Shaked. The code is released under the terms of the MIT license.
