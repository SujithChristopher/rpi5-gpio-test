# Raspberry Pi 5 GPIO Test Program

This project is a test program designed to interact with the GPIO pins on a Raspberry Pi 5. It provides a simple way to verify GPIO functionality and experiment with input/output operations.

## Features

- Read and write to GPIO pins.
- Test digital input/output functionality.
- Example code for GPIO setup and usage.

## Requirements

- Raspberry Pi 5
- GCC compiler
- WiringPi library (install using `apt` if not already available)

## Installation

1. Clone this repository:
    ```bash
    git clone <repository-url>
    cd gpio_test
    ```

2. Compile the program:
    ```bash
    gcc -o testgpio gpio_test.c -lwiringPi
    ```

## Usage

1. Connect your hardware to the GPIO pins.
2. Run the test program:
    ```bash
    ./testgpio
    ```

## Notes

- Ensure you have proper permissions to access GPIO pins. Run the program with `sudo` if necessary.
- Refer to the Raspberry Pi 5 GPIO pinout diagram for correct pin connections.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Disclaimer

Use this program at your own risk. Improper use of GPIO pins may damage your Raspberry Pi or connected components.