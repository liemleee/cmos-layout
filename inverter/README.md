# CMOS Inverter — GPDK090

## Overview

This project presents the schematic design, full-custom layout, physical verification, and post-layout simulation of a CMOS inverter using the GPDK090 90 nm CMOS process.

## Design parameters

| Parameter | Value |
|---|---:|
| Supply voltage | 1.2 V |
| NMOS width | 120 nm |
| PMOS width | 120 nm |
| Channel length | 100 nm |
| Input pulse | 0–1.2 V |
| Pulse period | 10 us |

## Design flow

1. Schematic design
2. Pre-layout transient simulation
3. Full-custom layout
4. DRC verification
5. LVS verification
6. RC parasitic extraction
7. Post-layout transient simulation

## Verification status

| Check | Result |
|---|---|
| DRC | Clean |
| LVS | Matched |
| RCX | Completed |
| Post-layout simulation | Completed |
