# Arduino Blink example

Based on the `Blink` sample from Arduino. Currently demonstrates:

* Using Dev Containers (tested on VS Code and on Codespace)

## Dev Container

Uses the `arduino-avr` image and Uno R3 for this example. Once the Dev Container is loaded, open a terminal and run `arduino-cli compile -b arduino:avr:uno --output-dir Blink/build Blink/`.