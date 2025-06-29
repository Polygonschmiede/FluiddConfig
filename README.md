# Anycubic i3 Mega S – Fluidd Configuration

## Overview

This repository contains a **Klipper** configuration tuned for the **Anycubic i3 Mega S** paired with the **Fluidd** web interface. It reflects several common hardware upgrades and quality‑of‑life improvements to turn the stock Mega S into a reliable, quiet, and hands‑off printer.

---

## Hardware Assumptions

| Component            | Details & Rationale                                                                       |
| -------------------- |-------------------------------------------------------------------------------------------|
| **Auto‑levelling**   | **BLTouch ** installed. The bed is now rigid—manual levelling screws are locked down. |
| **Stepper drivers**  | **TMC2209** in stand‑alone **Step/Dir** mode. UART is **disabled** because I suck.        |
| **Nozzle**           | 0.6 mm                                                                                    |
| **Electronics case** | Custom‑printed enclosure with improved airflow and cable management.                      |

If your machine differs, adjust `printer.cfg` accordingly.

---

## Requirements

* KIAUH for raspberry pi 4 (https://github.com/dw-0/kiauh) (i use klipper,fluidd, moonraker and crowsnest)