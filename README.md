# Marlin 2.0.x for Anycubic Kossel Line Plus with SRK 1.4 Board

This is a customized version of Marlin 2.0.x that has been configured to work with the SRK 1.4 board for the Anycubic Kossel Line Plus 3D printer. This firmware has several pin modifications to better suit the SKR 1.4 and A4988 driver. 

## Installation

To install this firmware, you need to:
- Clone this repository to your machine
- Build the source code using an appropriate tool (e.g., PlatformIO)
- Flash the successfully built firmware onto the SRK 1.4 board

## Pin Configuration

Please note that the pin configuration for the endstop sensors must match the configuration in the file `\Marlin\src\pins\lpc1768\pins_BTT_SKR_V1_4.h`. Misconfiguration can result in malfunction or damage to the 3D printer.

## Warning

Make sure you know what you are doing. Misconfiguration of the firmware can damage your 3D printer. I am not responsible for any damage arising from the use of this firmware.

## Contributions

All contributions are welcome. If you discover a bug or have an improvement, please create a pull request.

## License

This firmware is distributed under the [GPLv3 license](https://www.gnu.org/licenses/gpl-3.0.en.html).

## Contact

If you have any questions or encounter any issues, please create an issue in this repository.
