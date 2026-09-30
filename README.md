# Agilex 5 DC-SCM Carrier Board

![](./img/modular-agilex-5-dc-scm.png)

## Overview

This repository contains design files for a DC-SCM compliant Agilex 5 Modular DC-SCM Carrier Board that supports the [Critical Link MitySOM-A5E Mini](https://www.criticallink.com/product/mitysom-a5e-mini/) System on Module based on the [Altera Agilex A5E](https://www.altera.com/products/fpga/agilex/5) SoC family. The DC-SCM follows the interface and mechanical outline described in the 2.1 revision of the [DC-SCM standard](https://drive.google.com/file/d/1-SdSQvSWy5pNN_kBiyztblxE4jdyUe9W/view) specified by the Open Compute Project community.

The PCB design files were prepared in [KiCad](https://www.kicad.org/) 10.x.

## Key features

* Agilex 5E based SoMs compatible
* DC-SCM 2.1 compatible
* 1 Gb Ethernet PHY (Microchip Technology KSZ9131RNXC)
* DisplayPort connector
* High Speed connector in RPi 5 standard
* uSD Card Connector
* USB-C 2.0 port connected to Agilex 5E based SoM via USB3320C-EZK-TR PHY
* USB-C 3.0 from HPM
* USB-C port with FTDI FT2232H for SoM debug and software integration
* 2x BIOS Flash
* Optional on-board TPM connector
* 120.4 x 90 mm (4.74 x 3.54 inch) PCB outline

## Project structure

The main directory contains KiCad PCB project files, LICENSE and a README.
The remaining files are stored in the following directories:
* `img` - contains graphics for this README

## Licensing

This project is published under the [Apache-2.0](LICENSE) license.
