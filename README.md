# MCU_Datalogger 512k EEPROM and Timer

## MCU Datalogger mit Data und Memory
A professional-grade, low-power embedded datalogging system designed for high-capacity non-volatile storage and precision timestamping

## Project Overview
This project features a robust hardware architecture built around the ATmega328P-AU microcontroller. It is specifically engineered for industrial logging applications requiring reliable data retention and modular sensor integration via I2C, UART, and ICSP interfaces.

## Key Hardware Features

* **Core Processor:** High-performance, low-power ATmega328P-AU 8-bit MCU running at 16 MHz.
* **Precision Timing:** Integrated DS1337S Real-Time Clock (RTC) paired with a dedicated 32.768 kHz crystal for accurate time-series data collection.
* **High-Capacity Storage:** Dual 24LC1025 I2C EEPROM modules providing expanded non-volatile memory for long-term logging

### Modular Connectivity
* **UART:** For serial debugging and telemetry.
* **I2C Bus:** Centralized communication for RTC and memory modules.
* **ICSP:** Standard 6-pin header for in-circuit programming and debugging.

### Hardware Robustness 
* **Power Stability:** Strategically placed decoupling capacitors.
* **Diagnostics:** Integrated power status LEDs for immediate hardware feedback.
* **Enclosure:** Standardized mounting hole placement for secure industrial integration.
  
## System Architecture
The design prioritizes signal integrity and power management.
* **EDA Tool:** KiCad 10.0.0.
* **Voltage Domains:** Optimized power flags to ensure consistent Vcc distribution.
* **Communication:** Synchronous I2C bus with dedicated 4.7k/10k pull-up resistors for reliable multi-slave communication.
  
## Repository Structure
* **/main:** KiCad source files for the MCU and Connector sheets.
* **/Hardware:** Bill of Materials (BOM) and manufacturing-ready Gerber files (coming soon).
* **/Firmware:** C/C++ source code for the ATmega328P (coming soon).
