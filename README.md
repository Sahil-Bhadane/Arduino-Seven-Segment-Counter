# Arduino Seven-Segment Counter

A beginner Arduino project that displays the digits 0 to 9 on a seven-segment display.

## Features

- Displays digits from 0 to 9 sequentially
- Uses individual functions for each digit
- Changes the displayed digit every second
- Uses Arduino digital output pins

## Components

- Arduino board
- Seven-segment display
- Current-limiting resistors
- Breadboard
- Jumper wires

## Concepts Learned

- `pinMode()`
- `digitalWrite()`
- `delay()`
- User-defined functions
- Sequential program execution
- Interfacing a display with a microcontroller

## How It Works

The `setup()` function configures eight pins as outputs.

Each digit has its own function, such as `zero()`, `one()`, and `two()`. The `loop()` function calls these functions in sequence, with a one-second delay between digits.

## Learning Purpose

This project is part of my journey from C programming toward Arduino, Embedded C, and microcontroller interfacing.
