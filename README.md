# RapidCOUNT
Updated June 17th 2026

RapidCOUNT is a mobile inventory counting application developed by Rapid POS, built as a feature of RapidGO. It enables retail staff to perform accurate physical inventory cycle counts directly from a Zebra Android handheld device, with real-time validation, audio alerts, and direct integration with CounterPoint.

> **Note:** RapidCOUNT is a feature of RapidGO. For full device setup, hardware requirements, and subscription information, refer to the [RapidGO README](https://github.com/Rapid-POS/RapidGO/blob/main/README.md).

---

## Overview

RapidCOUNT runs on a Zebra Android handheld device and communicates with CounterPoint over a secure Wi-Fi connection or 4G/5G cellular data plan. Staff can scan barcodes or enter item numbers manually to perform cycle counts from anywhere in the store or warehouse.

- 🎥 [RapidCOUNT Demo — CounterPoint University](https://counterpointuniversity.com/lessons/utilizing-rapidgo-for-cycle-counts/)
- 📖 [RapidGO README](https://github.com/Rapid-POS/RapidGO/blob/main/README.md)

---

## System Requirements

| Requirement | Minimum Version |
|-------------|----------------|
| **CounterPoint** | 8.5.6.2 |
| **SQL Server** | 2016 |
| **Windows Server** | 2016 |
| **PowerShell** | 5.1 |

> [!WARNING]
> Your environment must meet our [CI/CD Connector Requirements](https://github.com/Rapid-POS/Miscellaneous-Documents/blob/main/CICD-Connector-Requirements.md) (server access, firewall rules, etc.) before any install or upgrade. Troubleshooting, manual installs, or follow-up work resulting from unmet requirements will be billed at standard T&M rates.

If your system does not meet these minimum requirements, please consult your Care Team Lead (vCIO) for an upgrade quote.

---

## Hardware

RapidCOUNT runs on the **Zebra TC27 handheld device** as part of the RapidGO platform. A SIM card can be installed to support use anywhere with cellular connectivity — not just within the store.

### Zebra TC27 Specifications

- 6.0" display
- 1D/2D imager
- Android 13 GMS
- Includes: battery, protective boot, USB-C charging cable + adaptor, and Zebra OneCare Essential 3-year service plan

For full hardware pricing and accessory options, refer to the [RapidGO README](https://github.com/Rapid-POS/RapidGO/blob/main/README.md).

---

## Table of Contents

- [Overview](#overview)
- [System Requirements](#system-requirements)
- [Hardware](#hardware)
- [Features](#features)
- [Why Automate Physical Counts](#why-automate-physical-counts)
- [Training & Resources](#training--resources)
- [Conclusion](#conclusion)

---

## Features

RapidCOUNT supports the following capabilities within CounterPoint:

| Feature | Description |
|---|---|
| **Barcode Scanning** | Scan items directly to record counts — no manual entry required |
| **Gridded Item Support** | Count items with multiple dimensions or variants |
| **Individual Cell Editing** | Adjust the quantity of a single grid cell without affecting others |
| **Item Detail Bottom Sheet** | View item details inline during counting without leaving the count screen |
| **Audio Alerts** | Plays a sound when a scan encounters a problem, such as an item not on file, so staff can catch errors without watching the screen |
| **Cycle Counts** | Perform physical inventory counts by location or department on a rolling schedule |

---

## Why Automate Physical Counts

Automating inventory counts with RapidCOUNT eliminates manual processes and connects count data directly to CounterPoint in real time.

### Accuracy

- Eliminates manual tally sheets and transcription errors
- Real-time validation catches scan errors as they happen rather than during reconciliation
- Audit trail of who counted what and when

### Speed

- Staff can count faster with a scanner than writing down numbers
- No re-keying of count data into the system — it flows directly from the device
- Multiple counters can work simultaneously across different locations or departments

### Cost

- Fewer labor hours required per count
- Reduces the need for after-hours or store-closure counts
- Less shrinkage goes undetected between counts, reducing inventory losses over time

### Frequency

- Cycle counts become practical on a regular schedule rather than a once-a-year event
- Problems like shrinkage, receiving errors, or misplaced product are caught sooner
- Smaller, more frequent counts are less disruptive to store operations than full physical inventories

### Data Quality

- Count data feeds directly into CounterPoint with no manual handoff
- Historical count records are stored and searchable
- Variance reports are generated automatically, highlighting problem areas

### Staff Experience

- Simpler process means less training required
- Audio and visual feedback on the device keeps counters on track without a supervisor nearby

---

## Training & Resources

RapidCOUNT training is available through **CounterPoint University**:
🎓 [counterpointuniversity.com/lessons/utilizing-rapidgo-for-cycle-counts](https://counterpointuniversity.com/lessons/utilizing-rapidgo-for-cycle-counts/)

For full RapidGO platform training including device setup and all available features:
🎓 [counterpointuniversity.com/courses/rapidgo](https://counterpointuniversity.com/courses/rapidgo/)

---

## Conclusion

RapidCOUNT brings accuracy, speed, and consistency to physical inventory counting by connecting CounterPoint directly to a handheld scanner on the floor. Before go-live, confirm your environment meets the system requirements and that your Zebra device has been configured by a Rapid POS representative.

For assistance with setup, configuration, or troubleshooting, contact Rapid Support.






