# guitar-tuner

A guitar tuner that detects pitch from your laptop microphone and gives visual feedback via Arduino LEDs.

## Structure

- `cmd/tuner` - entry point, wires everything together
- `internal/pitch` - pitch detection algorithm (FFT + frequency mapping)
- `arduino` - Arduino sketch for LED feedback

## Requirements

- Go 1.21+
- Arduino UNO R3
- 3x LEDs (red, yellow, green), resistors