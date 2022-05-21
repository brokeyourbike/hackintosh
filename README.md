# hackintosh

[![Latest Stable Version](https://img.shields.io/github/v/release/brokeyourbike/ocvalidate-action)](https://github.com/brokeyourbike/ocvalidate-action/releases)
[![tests](https://github.com/brokeyourbike/hackintosh/actions/workflows/tests.yml/badge.svg)](https://github.com/brokeyourbike/hackintosh/actions/workflows/tests.yml)

Hackintosh (i7-8700 + iGPU) - OpenCore 0.8.0 + Kexts + BIOS - macOS 12.3.1 (Monterey) 

## Hardware

Type | Value
--- | ---
CPU | Intel i7-8700 (12) @ 3.20GHz
GPU | Intel UHD Graphics 630
Motherboard | [Z370-A-PRO](https://www.msi.com/Motherboard/Z370-A-PRO/Specification)
Memory | 16GB (2 x 8GB) Kingston HyperX 8GB @ 2400MHz
Storage | [Samsung 860 PRO](https://semiconductor.samsung.com/consumer-storage/internal-ssd/860pro/)
Audio | Realtek ALC892
Ethernet | Realtek RTL8111
Power Supply | [CHIEFTEC A-90](https://www.chieftec.eu/products-detail/109/A-90-SERIES/112/GDP-750C)

## Installation

### BIOS Settings (version 7B48v2C)

Enter **Advanced Mode** and **Load Optimized Defaults** to reset the default BIOS settings. Modify the following settings (may vary depending on motherboard model and BIOS version):

Select **Save and Exit** to save the new BIOS settings.

### Install macOS

I performed the installation with the USB drive, keyboard, and mouse plugged into the USB 2.0 ports at the bottom of the motherboard. My display was connected to motherboard with DVI.

## Authors
- [Ivan Stasiuk](https://github.com/brokeyourbike) | [Twitter](https://twitter.com/brokeyourbike) | [stasi.uk](https://stasi.uk)