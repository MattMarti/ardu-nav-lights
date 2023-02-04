# ardu-nav-lights

## Intro

This is a Rust program used to control navigation lights for an RC Airplane with an Arduino Nano. I think that it would be fun to be able to turn on nav lights when the sun is low. This is also a fun opportunity for me to dip my toes into embedded Rust.

Disclaimer: I do not plan to fly RC airplanes at night, even with nav lights, since that [violates FAA regulations](https://www.faa.gov/newsroom/small-unmanned-aircraft-systems-uas-regulations-part-107#:~:text=You%20can%20fly%20during%20daylight,drone%20has%20anti%2Dcollision%20lighting.).

I made this project by following the very helpful tutorials:
- "[A complete guide to running Rust on Arduino](https://blog.logrocket.com/complete-guide-running-rust-arduino/)" by MacBobby Chibuzor.
- "[Rust Runs on Everything, Including the Arduino](https://www.youtube.com/watch?v=ZPSqhb4KKNc)" by Low Level Learning on Youtube.

The following sections in this readme were auto-generated from the following commands, with a couple of modifications.

    cargo install cargo-generate
    cargo generate --git <https://github.com/Rahix/avr-hal-template.git>

I chose to use the MIT license since it's simpler. Don't sue me if your airplane crashes using this code.

## `avr-hal-template`

==================

[`cargo-generate`] template for jumpstarting projects on common AVR
microcontroller boards.  This template supports the following hardware at this
time:

 - Arduino Leonardo
 - Arduino Mega 2560
 - Arduino Mega 1280
 - Arduino Nano
 - Arduino Nano New Bootloader (Manufactured after January 2018)
 - Arduino Uno
 - SparkFun ProMicro
 - Adafruit Trinket
 - Adafruit Trinket Pro

## Usage
If you don't have them already, install [`cargo-generate`] and [`ravedude`]:

```bash
cargo install cargo-generate
cargo install ravedude
```

Then instanciate this template:

```bash
cargo generate --git https://github.com/Rahix/avr-hal-template.git
```

You will be prompted to select your board - do so and you're ready to roll!
Everything is prepared so you should be able to just

```bash
cargo run
```

and see a blinky flashed to your board!

[`cargo-generate`]: https://github.com/cargo-generate/cargo-generate
[`ravedude`]: https://github.com/Rahix/avr-hal/tree/next/ravedude

## License
Licensed under

 - MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)
